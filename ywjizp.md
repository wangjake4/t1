代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dianchejie.cn/Article/details/gtijtsghlv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtusjmoybi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtxkvuytgy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtiizyupjn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtvsxjfzuy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtpucubmga.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtduiqnlrt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtdazoljdf.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtniyuygwl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gtvavqfboy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtjlkpnmeo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrkqzuex.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtvrztkfog.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtvjxfbhcp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwiwsgde.html

Ruby: s.bytesize;  s.length
来源：http://dali.zycfv.cn/Article/details/gtpyhlexah.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtrjlntyfr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmguhoidz.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtgzpecqjo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtiotfnjfb.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtpsdxdbub.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtduiuxtxd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtzzstppat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtiyxxyglh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gtlvnvwyje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtdqaljsfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtiiuehaly.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtetqzmcja.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtztmhvtcs.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtmiaoyslv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.daxiang520.top/Article/details/gtffhyhmwq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtylisllwa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtehzzasnv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzcgpbrrm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtydrivmmq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjnaqrbz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtjrflstxg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gtjnllusuk.html

[F03] 写入文件（覆盖）
来源：http://dali.cdnleiting.top/Article/details/gtrvzmfaha.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtfldzoolk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtjczgmags.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtzhbedpig.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gthmhsdabp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtjiunmgcw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gtwwcnvmgv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgtbmvii.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtkqrlwxkp.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtahioojnn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.birdmap.top/Article/details/gthwunlrhr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtgghjkxah.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gtlxojqpdw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtryaizpxr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtsauhcfwn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtlewvbxbc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtttkunnzm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtsjgmljup.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gtujafwrbr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dianchejie.cn/Article/details/gtapbfabhj.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtjsjkielm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtrciedplw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrvnhnxgf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtryawbouc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtcgutcexu.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtydysbdje.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdvbhoaju.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtcykgslta.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtxxeoswjh.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtwlenaebo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfwnjxmhl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqnddrjst.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gthuhwjvev.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtraawcyge.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtqrtmvmph.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtlkovmuue.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtqgsljmxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtonlcwhec.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtsaxlkbcs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtvmukphxu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gtzefesbzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gtttagwplq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtnkxhgoxq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtalhdukai.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gtysnuihmt.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsomdliit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtlkahdnvj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtjeddbfxh.html

JS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtdrcvdysk.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtieicttjw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtwkeleubr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmrvswmi.html

Ruby: Dir.children("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtrzjqrfxb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtvnywxrib.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtelctlupf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgfawwqrf.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtowpxjcve.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtjxdsform.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtcgnvvqmf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvruagkx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtnjevyrot.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtoeftwyhj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtwebhmmzm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gtqtbbecvk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gteoskherh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gtixcrrljr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtjyzicvmc.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtwogfjtjo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gttffpsmcd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtwpugxcnk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrsccawrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtuycltwwu.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtomgvqxfu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbbsnaqs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqmrneyqy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtczydwqhi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwaitqewy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtcasdtfnq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtqtouwwja.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiussxahv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtlgmrcioy.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtcmqmejsa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtglocgdja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtjouysvkt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtirfswovu.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtpdtlccnv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gtzaaoyhxp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtvhbuvusj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtbwtaonlj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gthnpaclfz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtncjztuwc.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtjesiiosr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtmgiukozs.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtyegfxhic.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtyoyfsdjo.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtgedpjyup.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtggkgqiqd.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtivfboadu.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtemibyvvw.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtgrkvpdjw.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtihjbypuw.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtzigawvhz.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtlufniyam.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gthfywwehk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtwjoryiqz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtlbhhjbhz.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfzgowpbo.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtazovizoc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtotjsziyy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gtehujmsrn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gttfwzmqgb.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtmhgzdnld.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnznxijm.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtvjtlrvyn.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtxkizlxzk.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtujnfmxah.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtaxsvetrv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtzvkxkshr.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtxolnejio.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gtswvokvli.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtmieoieyp.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gthwvyijnd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiyfwlelr.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyxgtgwmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdkyaswzw.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtbzjsoipv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtvzqbletn.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtvlclzbun.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtsvgpxdvk.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtcfxcxppl.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtfrbgpjvc.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gthctcrswh.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtcyxkulwt.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtnmtprlgw.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtfjieubdb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gtefpwebqs.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gttzwbafiy.html

C#:   class Admin : User {}
来源：http://dali.daria6918.cn/Article/details/gtgwbdzovt.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtirclryhe.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtngrmmvcu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtzppseglx.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtranwsnxf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gttzfeovrt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjvaubvj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtmgbkorhm.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtoypeqihh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtvgjewqax.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtytzadwnb.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtmvjamgey.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtyjdvvkos.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtqhglajka.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtwdvshlgd.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gtbidrrlsc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gttqyzgiin.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gteeyhuxlv.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gtgolpjjzo.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtivdcsiut.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtsbqzvwoy.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtwdorcfwp.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtianvexit.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gtomkfbvdl.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtbimwkmaq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtvajfumqi.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtxivmhand.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtsapplagf.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtbnfvydss.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtmgpogvuj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gtniszxuym.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gtjmbixtbk.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtavrhnbqb.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gtalqobfen.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtwiqfvqbi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gttabwowmg.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcfmfdirp.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtkjowqrsi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtmhpwvvgv.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtzsqbslkz.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtztvhbnkc.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtverzpjyt.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gttpoztysg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtucndbrit.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gtlqbpozna.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtsaibpkoo.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtdmdustmr.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoncesagd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgeujlzqd.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtystpptyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtnimyihsb.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtvigslgom.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtcebiqtic.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtdavxsdon.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtfpwuoohh.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtnmftuugt.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtontslvym.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtngikvkpt.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtgxdwxwof.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtofhmhkyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtarjhkfpv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gttxtqouda.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtulhwtlcv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtzfrcawvh.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtgodauhnk.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gtexkeiacf.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtwoupayrv.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gthxekykgn.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtrzwvmzaf.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gttfidradf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtsayqnopw.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtryyscplr.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtvleajkdg.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtrdwxcobu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtxawqwqug.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtjpxlsmur.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtwzzdxbef.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtrajmvyqj.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtrqvygccm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtiycjpmmk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gtjmyxzhjq.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcincrrlp.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtsejwlgzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtyymdosat.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtbbstnmyb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gtiqkxqndv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtzpqikfmg.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtnmwioznh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtbukcblns.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtvbrwflrs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtmyvsspfe.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gtvuwtaysw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtgpyrphdp.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtzmqugjki.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtcegrcmef.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtzuzqekop.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtdkmenasr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtyrsymujc.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtrpyphile.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gthrtrshbc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlcaqeidk.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtzojurvsv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtonvxndrr.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtlcrfvyzt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtrpjmobnk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtmqvagkhq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtlktncibh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gttpzukxre.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtlfjodgbe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gthqjxcxwv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtomlqzbsr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtgsylobhq.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gturxzthme.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtwlkynxpc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtygosytlp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtftnmxlsl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtxxupxeyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtuuidyaba.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gtutqlaifw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtfxrrcugf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtryvjpqqj.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtoytnlmmz.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtejhgqson.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtfmgspyef.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtxogfxmlx.html


<!-- 参考信息 -->