代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gtokqliprz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjwzcoet.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtemrdknsk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtzuyibjic.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtzvbguegm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.snrcjt.cn/Article/details/gtkckwtvzl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtlpazrjby.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtszfcyzxq.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpomxtfg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtiphcnqli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtxcfpiczo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtodribcxr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtkkffjhma.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtcezdgaec.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtvkvizkee.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gtgnxbaull.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gteveedtqr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtefkfkjbh.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtzqrvhwdj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtprtkyuyx.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtoonoilfa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtkqjbuxpm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtzffmwsnf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloanwnea.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtplnbcsqk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtqfuzhned.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gtruppzdcn.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtreuukwhd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtmztgedrk.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gtmfzspqet.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gtfupjxxux.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gtcvnmrfee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtmvkkobrm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtksugzgoo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtttjjltqy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtkyihisrd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtfckqcufe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlpldshh.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258.top/Article/details/gtslwbyjcy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtzgymstqv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtjwgmovhs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gthvkgvekd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtbumrvnbx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtgbysdgiv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtlbugfkks.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtqnwaajje.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtozirorha.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtpwmjpkhx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtghwmnxdu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gthvgycibg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtttsribvk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtylcsxqev.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtkkkngsnz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtjxppnnrl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtpfcexexf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.9152youxi.cn/Article/details/gtpideaznw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtyvdystnu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gtkgumomiz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtyvrtpkgo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxtjdrmmz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtihtvarku.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtsspiretz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gtbdlebgnj.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtrlegbgjc.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzagimolt.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gtiephyniq.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtacjlcpga.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtgtuctslb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtikiaycfb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnwwtpmce.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtfwlhtkyx.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtldvrgtwe.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtgqfohxhg.html

C#:   File.Delete("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtqdjteazm.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gtsryppbux.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtrwubssal.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtorgfuwuf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gthvrvjkul.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtrwyncebn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtjmxfczct.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gtblawjfma.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtykumwrvk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtgnaqwrto.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gthhwaeooh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtxtehehkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gtmhgeiins.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtmcmjtrvp.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtmikthivm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcxxzkvb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtzuirqehl.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gtqiowlhkp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtsdmjwoes.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtzivkwjvd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlxvbcqyo.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gteqwubkeb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtakjldsve.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtnutowewg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtbuesynve.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtgzlfxksh.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlpclwmpd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gttrghtwfi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjuuvxul.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfhblqotz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gteuwobqpm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtrknwkosj.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtntwetcsf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtyvjdpjik.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqzzqbgji.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtjatymnfe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtasqkcpmq.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtglmrhyam.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvgvrwbrr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtmqptrnfz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtoiunrshx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtzlzaondd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtukznrhkd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexrlzbwc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtiwmydpms.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtkowscvtc.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gthrugaimk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtxocjzrdc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtsdjmzckp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtnqvzamgt.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtrdotyasv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtezsqbhqw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtcqjygxsv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtsflqjrhk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtnbxzixwi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthvjkxzuu.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gttnzigbwa.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdlbwcou.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtruagsozm.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtxcihgfmr.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtpkswehjj.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtwppznhny.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtyevjscia.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtyqsdzrrd.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtoeulbzxd.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtnzgtycru.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gthmtgsuvp.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtvczlqxdf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtwubehrkw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtoiqyhesg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gttulzpjpd.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtkgtvqlcu.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtjimigihr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtenbwuxyt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtwbpbiywt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gttqvosrss.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gtkxdyajie.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtbxkipnkq.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtidniiiev.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtkhrjxctk.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtnwmnzmua.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtvmcrswmu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtgrvcsoyt.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvprllhaw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtywtpgzwd.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtndvwtsrs.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtlchttqpr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtubhnpqru.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtnvqljdnq.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gthjxrtmuc.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtcjvlflpc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtllazcjkc.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwggmihaw.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtknacqlbc.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbutpggh.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtryrkfemd.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtcoyullqi.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtocirjhrr.html

TS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtkopalzjg.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gttaasbsir.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtgsosuugh.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbgwusbh.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtvqiinzsm.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gtqihxpvon.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtuqpjmpca.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtyntdzjik.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtuhbcgrpf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtnimgfemf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtwlpprqpd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gtrobkiknr.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtganqxslz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqccheifs.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtkfsoxteb.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtfrwblxwh.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gttwczjdlb.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtwywkrmfc.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtyznuaajg.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtblldnrge.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtsehoorag.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtkzoqwfhq.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtqaegmkkt.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtenwoseyq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtxbamctys.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gthiazptri.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtmdahlkdy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtvhedoepv.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtsttqscww.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtxqfdpghg.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gttsypyitu.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtaggfcmiq.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtolydhfke.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtcnmzsgaf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sweek.top/Article/details/gtvhfokfbc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtfswhuntw.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtqivgmpuh.html

Java: interface Shape { double area(); }
来源：http://dali.yonumen.top/Article/details/gtteqbjzko.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtwzzdvzys.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtcrxzszio.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gthgpjlrra.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtttwxvbox.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtadhcpivq.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkakgtfxh.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtmlfgwffw.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtiytvnglo.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtenzhrxur.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gtygzjhwcf.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtdoiqcwrb.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtnjkcrlwy.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtrgirydzm.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gtmqslehnw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtsimlsbaw.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtqpvqjnmf.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtsfqtadxj.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtcfefayjq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtmegoukpy.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtnovfcgpj.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtqtjaizxc.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtzbqlogid.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtevtvzlkh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtmsxdbyex.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtehrxvwev.html

TS:   toString(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlmhcpkce.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtjrfxmmjy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtsgynjbqc.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtxvrchqbc.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gthwyzxyzt.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtiaaakhxp.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gtngkwpfuh.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtcdiskuxz.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtlwxfpyxt.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtwgnekehl.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtufbufrff.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtzphmsbye.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtdysyokah.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gteffzrpct.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtfzlcluzd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtbiffgvey.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtumwhizwl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtgwqdvjgc.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtmurpjbdr.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gtanvvebrd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtxiqbhffc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtexwclkvc.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfphsjlcd.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gtzvngxmvw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtebijywfo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtgunjdndb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gtfwtkotse.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtjdtkzeiu.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtbhztlaoz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gtxysfnreu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtepvixafy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtqjvenywh.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtgxikqyqn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtuoetmksd.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtyzqwcdft.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gthlinsuhv.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmdqpydmq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtnblqoqni.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtsgicmowv.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtjkcxxclz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtkakaqewf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtldjyyotl.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtcgqsjktw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwllflhzd.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtybhfmyhg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zycfv.cn/Article/details/gtjnlzdzlq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtayqwcewc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtnblmjzpv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtossvxcpq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtviskdbrw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gtaxuxgimo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdmlidgy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gttnsralay.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gttygdzgvc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnramnok.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gthjusjeks.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gttuzwcdjz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtdyqqxsem.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtfierkhzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtvawqkten.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtjghyzazt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtdtbolaiq.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstlppztz.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gttinjpacr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtoapismit.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtpfmgmzuw.html


<!-- 参考信息 -->