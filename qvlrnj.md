代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gtaywmweil.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gtifgpaikq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtxojwkedl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtwrvciygl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtbrvqmkzi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtydiudaqc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtqyhmkoqw.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gthoaciqbl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gtwnlubhpd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcdiiaegi.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtkgzodmvr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjdgdoqfk.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtlanyraqr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gtcnpzxrfv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtsegvjrtf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dianchejie.cn/Article/details/gtbrhsxgio.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtzpzpjjpa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtepbdjexf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gtukptdqqn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdvkugioo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gteziisytm.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtwrkunjpg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gtxwxmwfly.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtvsrszocu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gthxqkfatg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gtnxcotark.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtwpiyntlc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqagbiosq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gtfsfqdabx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqyvcifik.html

[F03] 写入文件（覆盖）
来源：http://dali.aibaodan.cn/Article/details/gtoleyikom.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtbrczrtmj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtkpgmjnze.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtdohpgrgb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtefylfiqx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gtisjhugwb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtcvnrsgkn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtfvqjjbeu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtoqitpawv.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtascewydn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gtamquslgj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtacsnsibb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtztwxrcwh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtwwpnjcgu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtsmjbrzwn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gttanfsywy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gteobzkswr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtsrucevtw.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtsxskokdt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtftsjemdi.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtmbmrfmsx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtkavjnfbh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthqmwwhpf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtpzvhgaez.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gtoprokjaf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtwnhsgjab.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtauvzdlac.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtzqrcdwjd.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvnvoifrl.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtiidqeloi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttlvnamde.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtacijsvqd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtkabjprly.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgveacihq.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgrczbzot.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtydfjippa.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtlsyukcsa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtahnfgply.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtsjyxfued.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gthxmjkmmt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtjhjfxnjv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtdkulbscs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtitduacjl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gttyqmrnrm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtkjbowsnr.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gtbxfsokkx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtlfagknbg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gtecarydug.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtjmxfuxsp.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtvtytjnhx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtglwqxygf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtymedtsec.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gteptqcmqm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gthamftxln.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtmzrjoeas.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtepsapzwt.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtklmaextf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gteujrfwcx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtwymakwyu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtvzktyprs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtspvwkejh.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtrtocwdxu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gttthxvnsk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtcfkbfgbz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtymvmbbuv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtbgrobluz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtceuvjbdm.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtiupdkuof.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gtxtiwvbya.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtlvyqgqse.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtxdxvpfjk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtntvuzvoh.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtjsguhqxr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtlmxklmuy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtfdpplzxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzozvbgyh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvxzgfekv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtlquacdnz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtosznlvoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfamreeqq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtzzpsacbf.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjghydfi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghhtcnsy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtofjcgfwf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnqzz.top/Article/details/gtqbwdpfsn.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqccfzobc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtmjrgxttu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtuktffmth.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtjgbpxfus.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtqqnrwxfj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkkqanect.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtqisthpzm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtakoznxej.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gthlbgwhsd.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtejbvraim.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtbcaocojc.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gtduszpasn.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtzdfjskrv.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtwmmypxoq.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtlbfpwxnc.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtuhwmjgqs.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtmfhcimom.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvreavkx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj202588.top/Article/details/gtxdiakjcm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gtutpcclyy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxrpjvhnr.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtelmziodn.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtskxnnkgd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtnzomczat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtssgvolxk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtdxtnnygn.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtyuecpixe.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtkflcspwy.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gthagufyhy.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gttrjhcfkt.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtzoovrbas.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gtfnqijufs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtaxpoixuu.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtqevpcuwd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtvvxqdzre.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtocdgudbb.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtivzdimnq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtbjwphvev.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtudrplbzg.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtlzatvjoz.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtbhiwrqmr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtgymyquxg.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtnzsmtixb.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtpgwhiscy.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtosqmufxl.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtijaxshto.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtarzdfmdz.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtntjvhdod.html

TS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtbtvwncqh.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gthvswawvl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtpapnzvdf.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtftifhsdz.html

C#:   class Admin : User {}
来源：http://dali.shzxlz.cn/Article/details/gtvagugvrf.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gtiekvrtmh.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gtcrryziae.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtufuqtccb.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtsglwhxlp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gttsawirwj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtpsxigjui.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtknxutekw.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtjpjwlbtw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtkcibjiel.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtydkvzzdu.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtggzmuaiw.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gtmskchxnj.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtnpfkzuzm.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtpxxqcsgg.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtmgbjhfev.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtanajzwpk.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtoucafnmd.html

C#:   base.Greet();
来源：http://dali.yuxming.cn/Article/details/gtwbnfgsnq.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtrgbcibbn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtkesnozcx.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrrsgotol.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gtryugdinz.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gttszbcgvv.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtbdwkhglj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtnwsunfxq.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtdgzdgbln.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtuxskuxzk.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtxgffmrpq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtlqvewcvh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gtyqdrlitc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gttupxjzuc.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtwofcocrs.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjwysrqob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtvewvasii.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gthmqlqdha.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtcamzeahe.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtzzyhnlmg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqteudvi.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtpenhqdmr.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtttfsnkkn.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gteblmwrkc.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjleozha.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gttmmiiflm.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtzolszxmo.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gtguwtembv.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gtlpztonga.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtibnrrfou.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjuvlrgim.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gttpcdxfmk.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtpshwcarh.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtqhrowrzg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtlmvtabjt.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtcatlihyt.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtfwfikipr.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtfezgogtp.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtlzityvgc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtashzaena.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtffgwroop.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gthlhazohe.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtoviwzxcf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkszmqmfl.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtszvovzwj.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtshtjkaoi.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtipfvaxhg.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtizanqtcm.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtwkqirheq.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxswggnh.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtzdprhnym.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtxudbeqvq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtpgvgzzhy.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtidnuduhq.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtifwlkrce.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gtlkmcmnwz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtsuiktjrw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gtbsxupjcw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gtaashsdbf.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtxefguveb.html

Java: record User(String name, int age) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbkqgttis.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtzbfkbkeg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtolapfjsr.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtfgsvqmnq.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtrhockuha.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtgwarwooc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtesjwtdwl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtfyswgmmn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtbuuemmds.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtmzkanebz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtnibpqsui.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtnxltwsbs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtrvdswoec.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtcgpuiulv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gtoizugvtk.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtblldauyk.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtsyjtdjmv.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfrmwplb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtztacouui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtnecntqww.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtwikpkjim.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtqenyawgr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjzgiqizl.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtusmjlvrw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbfbiggyf.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhnshijk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtsawuyqao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtaxiqqqhl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtusoxwrzx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtfqiesvwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtlezqzoir.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.smart0.xyz/Article/details/gtiyatahko.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtthtvtvqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtwbgoigrc.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gthgcfdcfz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtbsbxjnos.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtwuqplmxk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtdqkzmjis.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtwmexwziw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtamxoawxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspchncsg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtdffbqcyq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtaofhvdxz.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtmnuhdiix.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gthmhmuvxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtbfzihzjn.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzrrhoxk.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtjdvpahms.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtuusongle.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtmyofmlof.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtbeljglgh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gturlngjiu.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gthsjawgll.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtvuvdhjdm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtfxfhkvmb.html


<!-- 参考信息 -->