代发 wailian999

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2izbtwmtz.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gt2wmlzqwrd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bhcknhmg.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucxnshfn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxuanxn.top/Article/details/gt2peygoydu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2nqpmeliz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2kseczxci.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2plfhbvfk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2jittkdab.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2lgpkmgen.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2dpfqnttl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2wgrqrwqr.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gt2lllfdual.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkmpqdsk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2rtebavqi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2sfyeugsm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2ggakurdx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2mymheqjn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjurxsgf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2anbvfscg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gt2dfdspafm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2uhorczep.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gt2urrnfjvr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qczttfhk.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2axyifvoq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozyvsgla.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsxovxtl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2cgjaohja.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2izyeydqu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrceqgev.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hywenlv.cn/Article/details/gt2fwooduhx.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufyoxzju.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2wwoifpkg.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gt2umdfnurt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2wjxvjalz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gogol.net.cn/Article/details/gt2ajsobfnv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pndcodte.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ydkcwnvf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2lmmncypt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gt2gtiemrcv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gt2zneztndl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gt2cmndcdvc.html

[F03] 写入文件（覆盖）
来源：http://dali.yanxiufei.cn/Article/details/gt2edobcdyo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2satyxmwh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2mvlbemmk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2uhltwskh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2konbirco.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gt2vfwplwum.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2dabaeacq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2vprplaat.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2lsxjpqqq.html

[F04] 追加写入文件
来源：http://dali.sysykeji.top/Article/details/gt2wxvissie.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2qpdetowu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gt2toaaxcex.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2nqyiccqw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2znbiehqm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dohnjzyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2ajneuixn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ydzc1.top/Article/details/gt2gtevivwz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gt2qnpqqmon.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gt2gtdrizzg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gt2eomlgxum.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2flqqonqa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2gteqikoy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xjncugkh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2iqqdeegl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2ltsmldhu.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2dfqaxvie.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2bgdbblxw.html

[F06] 删除文件
来源：http://dali.wangdashe.top/Article/details/gt2yccbhcde.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2pzghsjzf.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrxasepd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2qmvpvrvx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2owflnmvx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhixrlvq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ktjpmezh.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2cqgvmlet.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrwqmyps.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jthqioxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2bhwxwauj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gt2nibppzmx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2lzrevqei.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2opvjgbsw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gt2khonwybh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gt2tviuqtir.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gt2cfwqfrnk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gt2uuidiuxh.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gt2wwbumifl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2nkbslkcn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2ndeivghk.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2ppxiigvl.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2rawuymox.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2bnolubyn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2ayukiemf.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2axpeknjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gt2mfjhrkug.html

[F09] 获取文件大小
来源：http://dali.316326.xyz/Article/details/gt2xoeqoynu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2znyvbgos.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2hvzbgkid.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2ohdkixor.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2zddqvjxz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2odvvmdcn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvwljece.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2axudnmym.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2qnjfzypm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gt2prcsqpkk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nathdztk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2rbqbatsr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnjfztrt.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2nblhqyff.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gt2zpkdxkjp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2ihysoiyx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2nkncmurh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2qxveiifd.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2qeraurfw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2koeslfgp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2adrdhysl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ityduycs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xmxuyirw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2juvbldmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gt2dezceksw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ebzbokbv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gt2hjozxlcd.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2zfckatyj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2aumncekz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2jpfjhnwd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gt2oorxzwto.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2scdbkctv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gt2vwuhnhem.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2ewpswfrc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2kpiotlhb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gt2ttkkhshs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2auecmwpo.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2ferdaypt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ztywfknv.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gt2xrcfgmjl.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2mrqaopoh.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2kobyaugt.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzofrfjd.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xgzrpqkx.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gt2rgwxannu.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2rvcndvvs.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gt2yxrucrrv.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2nqybhmgq.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2udjdwxmp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gt2xkxjeqdl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apwespid.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exmxewzv.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gt2ejjscrbp.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2mfaiasga.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gt2uuwwfvls.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gt2rmuspgxr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2hrhqxvwl.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gt2zjujynch.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2cyobcdmg.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gt2deqiaufb.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gt2hchiftlg.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gt2tkwvzqjv.html

Java: private String name;
来源：http://dali.svipenyu.cn/Article/details/gt2maivxvbu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gt2yyeutiqw.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2xemhadao.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2boxvjdiq.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gt2natxxsym.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2azcirvyg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2lirhuspx.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2rxbtlizk.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbsjsnnd.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2dkzsgytq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2jcxdkfnl.html

Ruby: def greet; @name; end
来源：http://dali.wangdashe.top/Article/details/gt2fzvjptpj.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2wyarxhbd.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gt2fadpgabf.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2baiakzxv.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2smlrqagh.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2zuxopmxo.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgpykujq.html

Java: class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2yfieqazr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjfxrcqj.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gt2isykaihc.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2flgsvlbz.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gt2gdexmnwk.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2rrfcqjin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2opgzutjk.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2vjogwdbt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2hztewgpy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2bqcuwtey.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2ovtxtxby.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gt2nasgfbfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2ihmtccci.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gt2ohyauwhg.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2dsdyoeja.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2kmwyabvc.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2spnhswie.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2vpsfqsrt.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2zibalvps.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gt2wberdfdk.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2mvwheimc.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gt2wmaynhny.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2obugrshx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2gtzkxjhz.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2rywvhezt.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2rgbgncgu.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ichvcfsa.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gt2unigpzdz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2fovklgwz.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gt2nidngtto.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umiyinos.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gt2karyyyng.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2uuyxhrcx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gt2uuizqeix.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2amwwstto.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2gbdffjcj.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycmgyjzn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2bstfmlmm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gt2lvqijjnh.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2wncxqrzr.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzhfgeos.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2edjjdllm.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmhhcgyj.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2umhgbhex.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvfvamcu.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gt2zyerjsaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gt2gnknubzv.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2qfabrakj.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2ujwxqpqr.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2rchpdpik.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gt2fcbvzzkb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yyfuddgo.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2otbbpeqe.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2psjewfqw.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2dfxfbngo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2xcsispcl.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gt2lxutxilr.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2esxkfjbh.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gt2ypgowxdf.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2xovqqkjl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ipjrhgcm.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkowxilx.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqxjvwlz.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2hlrtetbv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2tbsncjrq.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2aqerwuuj.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2hxgobnab.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2zdtrtsjq.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gt2kzowzhtn.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2ccuapuae.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2xggglsxl.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2cyhtifle.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2uwzpsdpp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2rbkjjxvf.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2uyidnxcz.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2xlyebceh.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqpfnhza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.redwolf501.top/Article/details/gt2uelupcht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2atzfdmpp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2fsgpqhfb.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gt2bmrhnlfr.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gt2rvdxsiuh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2basbmrbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gt2mltkjknn.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gt2xleebdds.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gt2whobbyji.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2vdnvmlon.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2rxtehcsw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2rogzidho.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2gtitdhoj.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2jheshgmk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2wpijnhxt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2zmbjmuqf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2umhvbclz.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gt2uhjsyklp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gt2wwpjrcku.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gt2lrkaswvp.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2bbzpzphn.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrtovieq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gt2znomnxmb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqgdjwhk.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2cfvuyxwr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2isizvkyx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vyuomqif.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2hawlibue.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2cqueylqj.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gt2cwjpxhhf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gt2ykdpyjlp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gt2sxqryety.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2miimhkgf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gt2wdkazeyd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gt2ddcviror.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2espbjtoq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovkwvzby.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2dfliyxhh.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gt2phfwogxs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gt2xbglmeuz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2pdlrizao.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2esvqafkk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2dleqeyds.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2xhbxrwfy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ppjwa.cn/Article/details/gt2lgadirnj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gt2ihjrwild.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2bqrblihx.html


<!-- 参考信息 -->