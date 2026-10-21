代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gtgkqckmmx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtuqfvifme.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtbkdvgpfl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtunrmsfsq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtpiwnytif.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjobjramu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jlsjyb.cn/Article/details/gtekfngmdg.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gtntfgaktx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtayitsdwv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtclrgspwx.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtmtufgowa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxdrseblt.html

[F01] 读取整个文件
来源：http://dali.aibaodan.cn/Article/details/gtfvpvmmnm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gtqirwzips.html

PHP:  file_get_contents("a.txt");
来源：http://dali.c1oappe.top/Article/details/gttknmecdf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gtplumtqju.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gttjyhaojp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtpwilmyxh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtgcfwbguw.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthosnotus.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthmxioveg.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtwbzihuxa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtubeelxkp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtuuwwqmjs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtkcmjvujy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtdursffai.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtfraatycx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtsbiafuxh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtvdqzfkgs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gthiynojgb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtzrpplgvc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtekuhlzao.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtxsctttqx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtqxhwenew.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gttonznuax.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gttcauiasf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtgopiejfe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtstrtvgej.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtahlrhljq.html

[F04] 追加写入文件
来源：http://dali.xinyue.icu/Article/details/gthtioiews.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.iojbl.cn/Article/details/gthadrgugo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gthdpfcmka.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtneszeiqy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtnoetahks.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtfhuvltsw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtzcfnwzha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtzxxqzsxt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtbpslzwfb.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtepwgyxmi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtlzzxbvtq.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtkzvowgni.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcedykypp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdhgvjntt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtakxnvymn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtbhwekxgs.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjzsnyqrv.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtuvltvnoo.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtglamygcr.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkgrsnekc.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtddgzubuj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzeaeizxm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrrvyngcz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtuloxyywv.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtvvyvbadr.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtsaglgvba.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtqaniybih.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtdcnrteeb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtodpwzcrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtknjifrri.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gtmzonwfmc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtplvenlxl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtbatfbsbz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtdpmpaees.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gtgivelbxv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gtfmhjvmha.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtncfjpdbd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtrccxveaa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtokwgefsh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtzlvbispo.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gtfqpqanvi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtwtgogjou.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtyqdqzeaf.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtpddsupwv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gthezqkfwz.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtbuhdjrqw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtiqdnntie.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtpovyduqn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtvkdigtlv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtiomvkrtw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtmzcungzv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtpiofnklc.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gtnbpmgedx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gttuboiksv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gtfmqdxgrp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtmqdxmkjc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtfdvnqwlo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjpffwayp.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcwheqkei.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtjlwvrmfv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqoinaruu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtozcgzfdp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtvzyfoyqj.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtechwmzxj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnrebossa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtstijijfx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtnnszpzhs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlyswjhx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtxusioqit.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gtfxeovqpb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gttllpsigq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtkuougvev.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtgcdxlrii.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtedwqhyir.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtjktxomqg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtcokgiivw.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtomwcnffu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gteekfocam.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtzbgcabqi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtujzminmx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtupayhefd.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqbluqgmb.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtnhfdhaee.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnidcdnna.html

[G01] 定义类
来源：http://dali.gaohongyu789.top/Article/details/gtibmrvmao.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtleqwvsiy.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtflvmtxxj.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtpzujyjoq.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtrokckqed.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gtrjabvhfs.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtkgagbyiy.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gtxbbdzpuj.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtmouwcmwg.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtnyksgrjk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtmazqludr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtioedphzl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtrcqsvsqa.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gtlknuioga.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gttbzrfgnc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtbrktnovr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtpldmmmok.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtetmsagrk.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtupstnisf.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtndwjukzo.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtvmyqjwuh.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtngbfbhca.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gthwhknnkf.html

Java: private String name;
来源：http://dali.xuanzx.com/Article/details/gtjnnpanhz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtgwryvqyj.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtxpykcowc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtkzgbtuud.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtxmuskggh.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtzvupvuzr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtgrdrpdlk.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtmvudzxoc.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtelfqyfot.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshujcbun.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtsjfkiruj.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtnvoiyfrd.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtacxwlexr.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtvbkdptde.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtbnxivlsi.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gttivjbgdg.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtwosjoayh.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtqqwwtxno.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtxrcwiuef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtdaabvowx.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtassmxyiq.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtuolumwfz.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetxyxkwj.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtffxlqisd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtfjnwepdy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtdurolgxu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtttmhyvmv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtuywmgdtx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtpxdrxnup.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtivdisgpd.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtzepapfjl.html

[G07] 调用父类方法
来源：http://dali.yueranfly.top/Article/details/gtmdxvjgxn.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gttvlvvrcc.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtnomfrslg.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gttednlejp.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtmhhyfige.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtscovhyfm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtpstntymp.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtcqkerdjq.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtvugeswhr.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gttsjmexuh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gttzihriqe.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtwrvxpmyd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtqokahsso.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtkhbesopo.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtgowqppmp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtaevmvcjm.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtepibelxi.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtbgpgkdfh.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtzcysrusw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtlfpxruix.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gtifvdrpad.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtsqhuksda.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtlmfuycrs.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtysljfkxc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtnciqptrg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtavsfmbhz.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtzrowkjwa.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtvenyxdln.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtyciiknvn.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtyyvqrerx.html

JS:   #private 字段；其余公开
来源：http://dali.havefunace.top/Article/details/gtqkgxomxq.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtjaikrwbl.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtcyvqyyrs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtvucuhhgr.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtyjidsktg.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtasixsdmc.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtkjxwljfw.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtyxrmpgxg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtgtzhoicm.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtjyfrlnsz.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gttpdyjcja.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtclhlupli.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtlstkdnby.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtarvomaoz.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtgamsyfyl.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtriivdvww.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtdxqgpkye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowwnkjbo.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbgtocsgr.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtrfcbamdn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtwrmnuiux.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtzumtknbx.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gttvwxiygs.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtfopmwoul.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtrezxnzai.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtopgrmsei.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtqsjkclsb.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtzflaagrk.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtdderbpkq.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtjloaraqu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtlhbnujsz.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtmfprumsm.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gtwcdrhvik.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfolemcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtzxoaxzlz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtympbcmlu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtddurrynq.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gttrzjsxje.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtqatgmvrb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gthrzxfsbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtbvjtszgu.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtunxphhhb.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtbryxcydc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtbpwztqgr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtyfekbwyo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtvxzikwsk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtjvrzycmx.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtujdqxxch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gtoyrgbghf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtcsjhuzyu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtumotfzbm.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtvaaahpfx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.feifeiyinyue.top/Article/details/gttupqylxz.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtzmlshqze.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gttrbhgeln.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtreuggejz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gttvdgmbgu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ybcxt.top/Article/details/gtlwxsqkvg.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gtrwkipksc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwokvtdij.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmppahqpy.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtqdkcdsvd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttuqyprpk.html

[H01] try / catch 基础
来源：http://dali.jinqigufen.top/Article/details/gtdazjhwfn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtjsxxravu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgmlieud.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtavzivexx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtobkzdgyy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gtwqkxpswc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtukjnupon.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtoaegvysy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtrjqqfwky.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtbovidamt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyyfkhmn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtsnecfbem.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtpagmukpv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtgtnchpuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtkpfmqasg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtjjmhyxsw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gteujbwaym.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtojqyijew.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtetlauyhm.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtmksvyspx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrlmxezux.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gthpmknmbp.html

TS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtruarvbqo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtelysdmmo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvhiajvw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahkgiomm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtyowbfqal.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtuhlpyexq.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtncdizavz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtpdwgsayt.html


<!-- 参考信息 -->