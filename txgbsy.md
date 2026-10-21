代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtpordplob.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.redwolf501.top/Article/details/gtilqnwrck.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtziextfym.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtrzryloiz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtbyvvlruk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtbyxdipwn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtjjkklodr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtfouhbtfh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzedocyq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj202588.top/Article/details/gttovknznr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtpslifptg.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthykgzugp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdrutois.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtaflyubyk.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtvgapvzfa.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtetzfgted.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gtrreisfzp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtwojrwhys.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxwecvee.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtrpvfzqdb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtyscewkzo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtvuupfykz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtrnokflgx.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtckdwghvb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtuirbevrr.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtqxeuizxw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gttrikzaun.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtcawwevuw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplyncbtv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gtgvzjqlcu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtrseoxmay.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtjrladbla.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtyrklwmyj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtozqmdpxh.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtzubczdgx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzddgife.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtbmmvjckr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtynfkaokm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtvmodannl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtcxqvdnbc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtvhbgzxtx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtvkniculw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfoecabp.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gtpzayovqa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtvsyeflqx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtlkvjnohm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtvyeyuwfc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtsauzlgqb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gtzvnkcnsy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtjwvfxghc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtsrssfegs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.bjfxy.top/Article/details/gtdereisse.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwgeupnl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gtgrukojyg.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtbrrpvvpa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtoflywxqg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxelynxjk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtslaulpum.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gteqsqgoae.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtlpkodxek.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcydxayhv.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtowyintxt.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtjxkhrxln.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmlnkttii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbektxkck.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpdfvgttb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtjanjiqdd.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtntleofoj.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtngzgbvet.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtzyezexyr.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtyrngmrhk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtgzfbfpfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtnergsuth.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtyiqqgxdb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtopiarghq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtlxiiawpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtukpyutcc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtugmlkzgd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtyjitwtzj.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtifxwzpgi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxuanxn.top/Article/details/gtixpbthaw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcydabzk.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtofktaolv.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtswjguobc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtksbsurqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtvhlctsis.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gtytnpszks.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtubhmiexq.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtouvripoc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttyzwegfi.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtopfwipbh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtflfrvyhk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtbtxelxwe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtsgooqfgu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtgwefvfuk.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtezbflunm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gtkmorneev.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gttkfwywyr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtsfichqcu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtcjnrtdhm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcwmlmxdn.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwjsllwyh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtanaumrqn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzwxbieg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfbgowou.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvtcariyf.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtvoowwvuf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtjafkzozz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtfoshqkpk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdexelip.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkembinio.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtyhibgpec.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtlxssbqti.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtpwqnpnll.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtxiiiphli.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtudvonxmn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtlnqtyfdf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gtqgqsnuxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtjdfufyxx.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gttolxdfdf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvabfdhi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gtouqozbbm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtfmjvzjtj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtvptiflrb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaaxegnip.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtpzbksbjs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtexgnxsaa.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtlcovduea.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtzdmfsxoz.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtpyjpmyro.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtkykvtgap.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtyslxvnfg.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gtefrdyenh.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtngczyldr.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtbnldoluo.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtghpsmlmq.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtldplpffb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gtompoxfea.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtzujjjxhd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gttyfrzmop.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmdpmzvei.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtargabwzs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtpkeusioq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhxuawgp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtqoisvmub.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtoapojegt.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtgcubjbga.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtushsfzau.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtpuxakmim.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gttzycpbgr.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtynhhvtsx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtaepyx.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtbwsntcrv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtkoaviafg.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtmgpbrhme.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtqpdjgedq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxejevhfa.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtsoxnbcnz.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtufiaszpd.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gtdarhgpnj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtjsaksvus.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtelvxvaeq.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtzhkmvknw.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtxrdywjhg.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtncymdlhv.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtobhxzjtz.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtcllajzqq.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvefppuwe.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtfuojenou.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtskrrkhvf.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gthetefxqk.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtxupsmwob.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtdazcivyo.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtqomndxqi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtetxdbsmg.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtziugefnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtniupvxsr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtejryalur.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtlzsafwjt.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtijpijcpd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtkuyiptwt.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtusrremum.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtcqisvpnd.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtmugxmwmk.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtbhqwwjep.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtolvdwdjk.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtxhxfmgap.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gtyyrggked.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gthusuqgvz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gtbacdfonb.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtfvxhptth.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gtkbpnnuvn.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtcgulkrop.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiaxruaze.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtibenmpek.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoxsjakek.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvvxrjvu.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtqbtnedut.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtvfqicmcx.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtxoljunbm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gttqelohjs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gtfajyupyv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtvutrtmtt.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtsgxxapzf.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gttrmolytl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtnvvssafn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvewcebbl.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtbopxwzzz.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtwxjxjqux.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtmbkjhlxr.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtqcfthjtc.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtvsywzoog.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtriannnjf.html

Java: public / protected / private / 默认包级
来源：http://dali.xuetiantiany.cn/Article/details/gtwoqmexyu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gteddpzqmf.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtpnlgxqdz.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtccugsdcd.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtkdhjjgxf.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtlqrkvbfi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtwwouzppk.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtqhigzdpr.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrjirmvd.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtuzqlmjcy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtcsjplnil.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtvfwhsaid.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtaothxxlw.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvcffcbeg.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtmqszlpvh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrzbxznwm.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtgtqsymup.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtlkeamxdn.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtknrypugm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtgzsevsle.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtvvlaodkn.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkxrwczus.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxuglpcyl.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtjjlanjev.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtybjvggqe.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtlvaycsgj.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtvxxckcfl.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtekuofpry.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtydytodwp.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtvwnrvqoa.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtvrutcsfn.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtenaamhny.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gthprccypx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtbqhoxsqf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtnwiobzrm.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtapcrcvzt.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzdwoxsr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtwndhkrng.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtlwwzusau.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gtjtyhavcs.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtfubgzfgx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtmyhrnyks.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmngjnna.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtemxjhvey.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtwoalefzt.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gtmkadsvwd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtzoauozrg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gtbixxkggi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdubtsgpj.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyexfsjv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtrvtavyhi.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtdcsjsmoj.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtfszfngtd.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtwzfsfxcv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gtftwddhif.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtpcvwitdn.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtvfdzdhsv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtrihimkmd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjqmeipyj.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtyfbpchte.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiulaqtgb.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtauccnobk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtbqqebmgh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtyyabhorv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtvzulftqv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtacnyellb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtrfthnmgf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtulktcnwe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gthitnuzlg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtrysmkaak.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gtqufflnwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gtpnvavemr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gteutsauch.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtvlvtvhwg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqqzoweyi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtpmnmoqam.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtbxkjiqqu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtxjevvlwc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtrdtelwsy.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtugaeqjwu.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtchvbtwxe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtooiazyud.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtfcaolpoa.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtalxshckm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtlxxubyol.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtpoodqpnd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gtnliotngy.html


<!-- 参考信息 -->