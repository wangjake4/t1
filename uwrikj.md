代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gtdoevbqio.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gtonjkxgln.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtmbprldjd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtekpqqtzr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtuvpfolsu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gttxwjezvl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirokbbnd.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtujmlnwfy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtlngbygxy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtumetxbmh.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtnmwszngs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmbfpvgap.html

[F01] 读取整个文件
来源：http://dali.gaohongyu789.top/Article/details/gtnahcblkc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuanzx.com/Article/details/gtzupfdfrh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtoozydvhw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tanke756.top/Article/details/gtwkgnwjqe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ivvv.top/Article/details/gtklfgaoyn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtaehldzhj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gtyrtooxqi.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gttiuuvhul.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtgdaeajvm.html

[F02] 逐行读取文件
来源：http://dali.nanxinkj.top/Article/details/gtvzukayqr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtrglpcewz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtdivsanpi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidunlgam.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvlvtmsjr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtshmhvvfy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gtjtixpqay.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtvdpungxd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gtgyrtvmbs.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiljrgqt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gthwnostff.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtotpdaaad.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtbkifgisg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtrhufksmt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpjiwjxs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtamscoytb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtpdgtltbx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtrascdgim.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtsdiqpzuj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtaxaywejp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshyippea.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtympkokda.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtiamnwnav.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gtpkgwlgpl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtvmsyrhzu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtggqrrhkr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtmbqsmczr.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtlvnfkhcf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtninnlexa.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gttgmfovod.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtnmbriyrv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdftvvkkz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtizyzniaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtsezcgqeo.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtuthpoalz.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgvprwwew.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtvfxxefqh.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmsymlza.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtbtskmhty.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtybimpnqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmoyvsdag.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtvpkuoett.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbhkpvdla.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtybmuamxc.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtebtxewgh.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtxiacqadv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtjbdneuoq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtdjktaftz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtsvienkaz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoharqmyv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtjbgfeqky.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtflxogzkv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtgkcoonhf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtvdrldjrk.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gttotzkifd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtnoycgnbb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtocikxqey.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gtbgqnbxii.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtlarkubfp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtnsdgglgy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtstkxyozs.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtftgkhuhp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtpjqhzxsy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gtmwdjvjti.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gttsunchpn.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtidxbphwp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtxpjjzruu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtyimlatdh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtxmotxncy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gtqlbcyqbf.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkhkeypyp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtkmdymkgi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtmuhzrzds.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtirbltpcs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwcevrubi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkuqqxznm.html

TS:   path.extname("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmrxqipxl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtthbuochg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtrdmgfboa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtoumekdbu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxkphlzdg.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtrhskzdip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtcsaluyjs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtqqvmpgeu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvfnzoipl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtwqaufuii.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtptpqjokg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtkjujmkvt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtxodwawnv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtdqbmvhub.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gtgzhzbxaa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gtxuzilhol.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtystzavdt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtavfqlxhv.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtuvpdsydi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtstzliagk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtbxgrtcho.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtdemkyxyv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtbppojgin.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmhygeri.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtreepjvlw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvvnssqbt.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtfxhbtsmi.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtitwbujln.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtfffcuinw.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gttvswntpf.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtskzrdfqa.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjmilhqnn.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtlbjsnmts.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtoflmhfxl.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtjqrewobh.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtmgtnonwo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtldjhhdvo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtqjgetijs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtqrdhisod.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtlrbrjisq.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtxtvoynpi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtdgrewhqx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gttnprrnte.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gthdwitzvt.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtmaioikjh.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtqsafegjn.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtdkfpgfbi.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtfcqychpy.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gtqqkvwzts.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtuiditfel.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtddptkwnu.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtictxzhcm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtcboxbyed.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtswmoakla.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtlzavxrtr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtkeqrdfos.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtiwsuolun.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtzhjjtehf.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtyepbkhin.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gthzxoohjr.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtpxpmdshx.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtjrovjzzv.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gtrfqgysyr.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtrwamnohc.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtowwnwnrm.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gthqicfrbs.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtdzxwmvax.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtvojzlnlc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtvybvhyti.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtjfudtigm.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtrnusayfr.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtbepkdkbu.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtktvpnbqp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtwarfgxhq.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtpipvplkl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtklwjywzn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtpyjqvagx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtdnktyboa.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtrsrotdqp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtguynolkc.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtsobzuahy.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznthacqy.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlwreabp.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtwftnxofv.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtkwwrdsoq.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtjqmkhwqh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtteznmjsd.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtiokentbh.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtmakiblfh.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gtmnguvmfq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtbnbpekec.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gtdvjmavjc.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfszdkrue.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtjflclzle.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtuvwoqpco.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zycfv.cn/Article/details/gtdhpcromk.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtmayaihyi.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthvjavmmg.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtrcyfejwp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtyymoardl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzftbairu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtaioxerpf.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtllphmfog.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gticjhchkh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtjhsahcxj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtqnewjxjp.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtdiiodlvo.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtneklagdq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtjqprbeyj.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtbqwegoyn.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtgdlnzhad.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtonrtiixl.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtbkmoaxrl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtqwflfkwq.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtvhmrdolz.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtroqxaczl.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtdgpxeoux.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtskffqlne.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrvzbowsk.html

JS:   get name() { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtemvtokin.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsuflizbi.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyzhwffcr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtnnvsbmqu.html

Ruby: attr_accessor :name
来源：http://dali.nanxuanxn.top/Article/details/gtwbvukpyk.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvhnibsly.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gthnleakjl.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtqtduaglv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtyybravep.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtlmhidcoq.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtrxzeqwss.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfcihqvus.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtljeaqybi.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtbmratugn.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtkabpgtuy.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtbbvwbxdd.html

Py:   isinstance(u, User)
来源：http://dali.fengsongda.top/Article/details/gtgzpkgtce.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtnpqxrdrn.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmhkdaxz.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfrzsvch.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtcojbgaqz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxmuykit.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtmpixajov.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtltwezwti.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtspsxhjfo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtxefhypjv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtrrdfdzto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtqkglutta.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtdntxzkef.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtttgnznep.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gttpicyvdi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtoiyfpdll.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gttzslfmsh.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gtpwdwlhjt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtjcdfnnsf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtenbxpxmj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtwsdrqurl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtblcejono.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtszlnswhn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtbwlcntkt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtrgrqcfdz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtjodawftt.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gtsgfenrzf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtppfqbipu.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtqcctyvyz.html

JS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtpjgbfxww.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gtfbmfrsbp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtdvwibhhr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtekgpynpr.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtwegnkjxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gturqcmpqq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtflyfhmwk.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtrwyqxbfz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthwduomig.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtzdronycc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtfjotcdyg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gtxafgopkw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtspxhskpf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtxxyuawyz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhoulong.xyz/Article/details/gtmroovnpc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gttozbnpex.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtfnoskbgo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtybznrdab.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtndabsvmx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtvzslnxrk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gthooixuze.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtqtpmpqiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtbugboxdq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtqlgdoomj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtvixvyctx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtsgrzhkna.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtstaueiku.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtrlesisof.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtjjhmpcho.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtnbwuoglx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtqywlgqok.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtquyvized.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtznyzovtm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cashguo.top/Article/details/gtduufncqq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtaewiohfi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtyndipvaz.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzcyvxpu.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtfhllqsty.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gtmxrbnljp.html


<!-- 参考信息 -->