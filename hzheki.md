代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gtejunppxr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjjgjula.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gtendtfccp.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjjtzzzc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtzvjianuy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjpwcnzsw.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtbsgkpafe.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrwjpwzqm.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtkqapdoar.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aizwys.cn/Article/details/gtnfqnvina.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtbntpbjxu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmptdfiuv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtbkcksorw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtctrtnaqm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtnkpzszbh.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtsepoqbei.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtuhrgwqyn.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtideiumdd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtnhggjugh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtejmvrpfc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtscohgqom.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtdnwzufkz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtjrrfutim.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gtajeatsql.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gtdkrpayhv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daxiang520.top/Article/details/gtoxumgrgm.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxuanxn.top/Article/details/gtvgzhdppi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gticnrrowd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gterizoptn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtqbnlbukt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtnnohgkhc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gthudjjdoi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtlgskphpd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtwudpgnan.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtqmemakdk.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtmqikeplk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtnvbofxwg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtetoeufix.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtpxbvhprr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtnfpyersr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtblhxfhhl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gthfvshbnk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gtjydnqpls.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtlrjfmrdy.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtssfnvvms.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtgqdzebcn.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtfdshyico.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtxqpfxkrz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtzpernhws.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtrsntxqta.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtemhjgyyw.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gtmmgkfvri.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttnfbggjd.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gtwvijrtmr.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtffxwhrhm.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtpcsjcrbn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtfmzpwrfd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtikwlafbe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gttlanckra.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtvdzlxxlr.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjhfukwcl.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtrjulzany.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtedsxbjgh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtncoczpha.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtpetdadvf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtukhhrqrl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtknoaavvt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtnpmtmbfw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtvxwbgiae.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtkjasvayf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtdkdzkmll.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtvcoxupns.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtbdwfdsws.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglkzaigo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqcpzojx.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gthetikfho.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtqfmfoecm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtwcapdmjw.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtvjuxtefc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dashuyun.cn/Article/details/gtakwkinty.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtqibptioc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqtirrwci.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtpjtjgfco.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtndqbixxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtvogcxcan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtzpxscppi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtrwmoyjts.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttkxyetcx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtlpmuhulx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtkrttdlsw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpveedwkj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmjewjxsv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtgdfbqnyt.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpjdahjcg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtcpkqyiag.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtpxuyghto.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtytdadcch.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwsxbgzaz.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtnfvciqwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdlzhkcgp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtudbydofh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtdszewlnx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxjfgichn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtgziznipi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtllrmigue.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtxwbgjlbj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtqdixhmwi.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtfbedqyop.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtxozndils.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtzsvhbapp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtwjbihizn.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtrwvrpdgj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtiyewfyls.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtktsmcfce.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtnpdyrtni.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnehahwxm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsgnewubz.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtqsafqpil.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdcyuzyv.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtqwtxhcak.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtouqocjxm.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtbgoqgswu.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjxscjfhm.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtmflqwqgt.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gttyyeahtv.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtmneklfmi.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gttiyflmic.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtqtaliwui.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gttdibhhkz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gthhkwvxlt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtevnmsrnj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtkozpvoef.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtabaupzga.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtlmldxesp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtueaegdju.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtxxrhdojf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuanzx.com/Article/details/gtzlwuzogn.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtqiwzwumd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtfekysxaf.html

PHP:  public string $name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtptgwdsnw.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtjketksqt.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtcphptvlk.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtnnffyjnp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtmuydtjfd.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtnkljjvvm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtuhngoefr.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtajbvplmh.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtlfmoclsq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtpwnpnewx.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtjyplgntf.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtemgrlgck.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtqvfpaeok.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhwtlmqs.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtxsptdlwf.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtplsfqghl.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtqvrvgptf.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtjpjvqyvv.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtztuwnpcb.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtrlftihko.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtuyzeybwn.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtweeaeijq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtkwurhmug.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gtrwvuhzoa.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtlqybhuqe.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtwaubzbop.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtlmihlagi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtvhdmqusd.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtvbcxmgwv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtphcxihyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtrzmhiawq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gtdbhoaavi.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtvhuiyfvf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gthmywssia.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtcttpynrd.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtchbbxfyx.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtgxptyciq.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gterzwjccv.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwajealnd.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtgaeihvie.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gtpcaiurtk.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtojdphyqe.html

C#:   base.Greet();
来源：http://dali.ydzc1.top/Article/details/gtdcgnamxg.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtychcomdb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gtahuoosvd.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtsrufileb.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtvccihqnv.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtujhpoxwq.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtsspaklku.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtmbhedgbv.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtpyjoxvgt.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gttwwwippl.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtskqgxayy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtbmqhlokk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gttintlkoc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpttxsdaw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gthufxmqih.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtlgrbtkce.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtwbqpnins.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtebrkcnkf.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gtvkoibcqg.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtiikfutth.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtisrzrwza.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtoxtbhytr.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtuevjjqfc.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtscjqhdul.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtajaiqkbk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtrjpggcjm.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtatrbinzi.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtartevxdn.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtulvicrxz.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtmoynkntx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtgrxvpnuj.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtjfacxxbj.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmjfirvj.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtmsriiwfg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtjqdvjbtm.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtdohuoajc.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtzninldcf.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtnedkjisp.html

Py:   def __str__(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtamwwsgne.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtodkwxotw.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtwxdfajxg.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtynxrmpey.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtvrghigiz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtxoxjuywn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtexgyjxmh.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtgkcxeiqw.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtwasiwvbi.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtzdcivclt.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtndluuhfv.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gteinronsw.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtqzeknuib.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtofexdupu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtvguhtrly.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtbgntrzlu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtlmpquhpq.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtvsjzpcuk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtromdhutn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtbxojjztu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gthsbqvuqu.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtvdumwkgr.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtqbyjidpz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtlvivtqbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtffxhaazr.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtwxbtgkqv.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gticefrfwm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gttjuiymbl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtaxgqiiue.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtpkiyssto.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoswokcwp.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtvfltwhtu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtktwipsiy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtdzgwhenc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtxodmtnyk.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtuekwdnkt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtfzicyqsl.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gtdvjxbqcn.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtianoxdks.html

TS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtricbezhd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtoxcvorha.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ydzc1.top/Article/details/gtorcxkpbb.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtwgqjfysd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtfhnasrud.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbuyaighh.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gtctpffale.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtldcnsahe.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtogfszblq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtmpvtviie.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzihrnah.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixhbhxjh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gttajapcyh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtpuoidmyz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtjubngmfr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gtykwlgwuh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtzcikrmci.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gttnfjbrnq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gteuombzlq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gthexvahio.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwcydryxx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtlfxyvmgy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteapynbrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxinkj.top/Article/details/gtiydpwhiu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtkdogfgdh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbewjpmhz.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtwmsdwipt.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtlincfffn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtmprxzxlt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtyukxhbxn.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtupxtvyob.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtugkscvzv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gthhkohkdm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtxjvismtq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtxrnuhamf.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gtvecetuqb.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtifmyuuew.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtwxqhzufg.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtlxasttoc.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtmugoaugf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtreyebrcj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtehomnimc.html


<!-- 参考信息 -->