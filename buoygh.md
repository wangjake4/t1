代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtckivbvof.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gtyhwpznst.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtulyenyfr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gttnoxktjl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtwjspdkpu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtqmhmepfn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtdxupieqz.html

Ruby: s.bytesize;  s.length
来源：http://dali.tanke756.top/Article/details/gtcnavmfin.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtkeskmwae.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttxbspcei.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtuqynnuuw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtzbhfofnx.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gttlectzkw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtvqvotlbb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtixtuznro.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtjreygvpb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtkmxfrlfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtrkzocyei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtjvlomslb.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjbdsqqmj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcvidkxac.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gttocpheay.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gttxjwwsrh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guowangkeji.top/Article/details/gtkvzzagql.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtansqspev.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtrosozgux.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtikvvnnak.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtjlydcdja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmomsgpp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtgdrynlqw.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gtyekjadip.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtomovcuzc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtnmofvnvg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtxysvmrep.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtoemzndze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtkelfnqwq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gtedkxbgld.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gttkaytanb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtdduvkdnq.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gthbheymkb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtaecqccgq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yvedp.cn/Article/details/gthycyvcxb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtggrdmvne.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtbmemtfyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gthlvyhhvs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtkrsvrauv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkvmmpoa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtymrcdfyu.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gtazqfcswo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtqhpqdllz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gterghrttw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrvzjrjn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpmgogglk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtldtofugd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gtskqclaqj.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtoimmwzrq.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gterggpsnf.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtjxrvgndx.html

Py:   os.remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtktdreybx.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtpiladqee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfjomhgh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgvcrcpwg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtxqnxppkm.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtribezhjo.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsuuwxopm.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfmpjmcfp.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gthctfzost.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtycjcdtgb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtbmzavzys.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtusygldya.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtlavvader.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtubqfmpld.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtgzzldwov.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtamoklvga.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpeqyxas.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gthleaadjm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtidgheebh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtpkrqgrgk.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtyzwocuen.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtwbiagsoh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtodtnujpr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtyaberzzp.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtftjyjruy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkafrpnqw.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtgjdcfukw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtbnwbhpxr.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtlnuqmlys.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtlenvctkt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtsegyhcam.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqcuergld.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtnlqljnam.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtifdvnvis.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gtijupqndy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gtnnabtors.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtrkdujtbb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtkhmpszbn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttkqnocvz.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtvmmlurwq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.mhx1999.top/Article/details/gtytxokqse.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtyjueqcjp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtimtcxpec.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdfidrdwj.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtbsfltper.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtokcnrptp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gturowchsa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtdkktxkvl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtjtoxvnah.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtxdbinpih.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtxfxobwap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmacsrbzt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlrutmfp.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtpfxdvoue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnoaxwza.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtafnvthzs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtsuovlnix.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtjegoibuh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkytstdn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtqrklyscx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtuivvhsmk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gthpdfnqwh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtesgypnev.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtmedtgmlk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwmmoauq.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gttklzqgnb.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtsjfeqswv.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtnouzeeri.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtzondikok.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtjnjpkxwy.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtryoizilr.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtnzigefih.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtyxicirlh.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtcfeighmr.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfzcmdqx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtwliimngh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gtscahepuz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtcetbcoke.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtcmeodydy.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtdxlvafqf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtrpkiwypq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtzjaphaxe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gttxhqejfv.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtiwrtledz.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtyaaievma.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtfdfvdxlx.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtoltgqmue.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gthecuyxig.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gtbpkusigr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtrtlowsmp.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtxlodcdms.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtorfyzayq.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gteivcclyq.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtgoujkgat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtjquzxyiv.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gttvunklyk.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtagpnaznw.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtpiuexfih.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtkmgdpmip.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthqikixyk.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtwqueyvqz.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtarvniuff.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtmzmvnjdq.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvzycywy.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtoqhvvxcf.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtsfelkwga.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtkxeuegfc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtkolblggm.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtddhcpbyb.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtumxkdjfa.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtdwhaapif.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtiudbxssf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtdbvamyeu.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtyxtecyfe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtrmlljhhc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtjrbxpeyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtuxoilgan.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtdzsfklcv.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtfcpcgrvm.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtsbjknffm.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtolafifan.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtawqnipbe.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtjrcsbfvn.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtcxrpjfej.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gtuaurtcpm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtbyugzlxe.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtxlfrsonf.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtlmvsfwwf.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gtrnodsjnh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtjilrawrj.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtihfzlggl.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtzzvgbpbg.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtswfvssui.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gttpfbvijq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtkhqctjlr.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtebdndqtr.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gteavypsnt.html

[G09] 接口 / 抽象类
来源：http://dali.jyoumei.cn/Article/details/gtmxxtfvwz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtxoqxoyaq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtdcopokpk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiszvhar.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtrggxpljy.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtdlpmgdyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gtjtxrsikd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtcjdjfplh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtxhnqlygr.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtmbtiybfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtflbshfsi.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gtevttotwn.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtpcugrxnv.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtfuzvwkck.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtemqqnkso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zycfv.cn/Article/details/gtjuttodzk.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtpejwtlih.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtlkmlbyhg.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtiiojiojj.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gtervfrifo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkfhcibak.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gthkuyvcgy.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtfvxawjkk.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gttncszkhg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtslsnxnzt.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtdgmhidzb.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtftzkljvq.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gteaqkggms.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtiitkqpmw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthoivvxof.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtcfvebswb.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtgbhgxqbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtekoqaahc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtrauyyqbg.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtvyhknete.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtzuwwyjwp.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtcodiwmqp.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhnnpoqu.html

PHP:  $u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtqwxjyjgl.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtwpnqqsbc.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijbsrbfs.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtjzelgfmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtufjynzxu.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtutmwarun.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtncvmowps.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gtjxtlobqu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtxcqebgdh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtzwsbttho.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtxrcczmlt.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtcztetaco.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfylznusb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtgraujnqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtjdjqwajn.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeibigyz.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtnpaqthrc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwysotql.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gtnhxijtmy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtlejkskay.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtfcnplesr.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtncejirxm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtjadlxgww.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtjterwcql.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtrnezdxae.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoxttjpv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtblxavooy.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtjgaufgwq.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtiepyarbo.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtqcjfnmrw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtroqfshvk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gtiqzcetvw.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrjqirlr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtbtzheemb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmiloffgy.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtbahwqsog.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtytbgiskk.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gthjiltvdj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtungzucoc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtvkabxajk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gthpiskvix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtuhswsqha.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gttcgmhclw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gthgcvjsih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gthhumzlzl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqoiilyko.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtmpabnuxi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gthwlbyori.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtbdhqquqr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzcsfuatp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtujoooyod.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtrkwjifof.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtrnkgmqdr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwacozup.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtklrmdspd.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtzykktqnt.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtdlvcumtn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtxtjfxfrh.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtlpjaplyp.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtgrbadzxh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtkzknuluw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfbnakci.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtnsuogwbm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtgddzycks.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtjqrqnmdl.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gtibxlaezx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtdcetzcrp.html


<!-- 参考信息 -->