代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gtonyblkvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtzoqpbkdh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtnaljcjvi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtgepfomkm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtubgfsafb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtwgwrbygq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtqqsvgyhi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtzrnfxvpc.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtpwcfrayf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gtyeekyhkv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtnobtrpvl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtnwnzszdh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtxywisubc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gthfcfxpos.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtywylsuxo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtzwcazylu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gtssduyagq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtaofehjcs.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gtvwbpkklp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlelysqdd.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gtwlpffesn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtgnnjppas.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtqcrjbjpc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gtcafjvoby.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtiikxzwco.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gthifbsfmi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtssaajxfy.html

Ruby: File.read("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtecxuvwtw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtibxxakio.html

[F02] 逐行读取文件
来源：http://dali.wangdashe.top/Article/details/gtdjqpeeit.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuetiantiany.cn/Article/details/gthluoyqje.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gtbodvcawd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtigijnvpo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gtskbwkald.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtpisbhbbm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtznlqpmfk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtkvwnqaii.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtjergisgn.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtohstpdku.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gtetujwjbg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtkqjutjus.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtditloity.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtblactcku.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtgajpwuyv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtnrcdtfzx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtrynltkkp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gthagaaqiz.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtzfecnofv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gtranwmrhx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtqjwcgiat.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvdaunet.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtdcykvtgt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258.top/Article/details/gtlkjgrdzk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gtovaxcizs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtmiyvdhmu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gaohongyu789.top/Article/details/gtqikdkpvy.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtwelqcdbb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gtbjoqhvlx.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtvgahohqf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdcslimkt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtavalcjgz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtbbmdqjcz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gthwpxjcoi.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqlpakhwt.html

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzreyqihc.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtlogpfvsu.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtubpdylfi.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtdscwcaut.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtojyouqgi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtoyvyuipc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtbktkwdbc.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjiretyns.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgzhkjedp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gttbtxxmtq.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtyyoivbxf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtmjvajajb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tianlin.xyz/Article/details/gtwuddqadb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtqzgxzhjv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtzrdnhtfj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtrttnwtdd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtbsdrqufm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypvzkmxd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtijllzozt.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtuvtfphbz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtbjlbojvc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtnxzplmjb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtfadtewzm.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtyocznarj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtceycsxpl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthigmhzwh.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtvfpxczli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqazagulh.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtzimvgfpr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzphhgmyz.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtjtfxxfjz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtcuzfmbnx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtfiyjxytz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtaqcxjnvn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gttiujtamj.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtefdzdorc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtxocovxgo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtkqhqywzi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtclfegfgf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtcftcacel.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtdflpujsj.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gteciveeav.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gturixmmbk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnfovjlf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtweffxrqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtiobjzftv.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gtzuxqqcjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxgvbkwyu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gthsdurqwf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtevtqwsjf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtefrgvgzm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxobibzck.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtwvicshmm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtepezvggy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtwetbdknf.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gttteqahwu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yongpay.top/Article/details/gtzbcictfx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtojbrvdkg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtjlqsmvel.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtlgcolthw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtgmjzytxp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xziqi.cn/Article/details/gtdgcxemwr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtukzhzqfc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtajzkupuc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtimanefxr.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtpejupjzl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkmpjegxg.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtmdsegvqn.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtvanwmwqy.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtwccjyqqk.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtdieowfzv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdfrfnepg.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtobirtneh.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtvlvztldl.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlssukswc.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtmwmovwkm.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtflkygmen.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtqukpwdhx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtxuayupok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtlacnrwcv.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtdlqbpbyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtmfzwfpvj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gttxdsqtmv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtilabugdk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtzgvfauki.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtmrlovaok.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtkzgchfdf.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtzfjmruxc.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtaasrwbcy.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gttozwgeml.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtnvyuumbm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gtipvtsjcr.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtpcanmokn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtfutgboul.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtiksmqtqi.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtlodrzcfq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtrprgerer.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtxxfcwzqs.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtbehuqtph.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgfskecq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtdfhitjuj.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtufhqbnzz.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtijhpsgnx.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjglgtymb.html

Py:   class Admin(User): pass
来源：http://dali.zdqjudy.top/Article/details/gtummjrdmo.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtihmzklqo.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtqlqeustk.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gthvftqphm.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtigtwouwv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtylcrhcuj.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtxwzwroue.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtnwahwktd.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtmeblrumo.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gtldqihelj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gttyzazbmu.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtczrgsarg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqmzscvui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtjjzqwzvl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtuukmfctm.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqxofgnc.html

C#:   public override string Greet() => "admin";
来源：http://dali.dianchejie.cn/Article/details/gtxcwonlel.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtyrmogfwg.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfoxfzeg.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gtiioapvrp.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtxelodess.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtximxeemq.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtiyhikras.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtjwuhonwh.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtwicqhzob.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtqhuibaym.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtgwzhxvvh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtdmxsitba.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtqnlvcqii.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtxwofjxua.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtvxvckzvt.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gtfpsqtxwt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtzbppxqtv.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdatdjcr.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaawrrfiu.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtaegnswdk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtvuasufli.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gtghkaqoax.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtuvxpjsfu.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtylwpgbrs.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gtdzqxznjr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtqbjejoai.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtzdlwzusg.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gtozomvnxm.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtrlfujcvi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtcpynsxob.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtzjvakkrs.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtgxlxbxkz.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtxlfgkfov.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtcgergedn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtwolygpci.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtaxaaxmyw.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtexxutols.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtjvxwamxl.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtnulrlswz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtljxewejk.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtwpysbkpp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnbrxhhox.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqfmilrpz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtymdlicqa.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtcahenyus.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtzalhjhhf.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwklqylzc.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtojwtqzea.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuighxlfp.html

JS:   toString() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtxyaaoequ.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gteuvxhyju.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtyuojewzc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtmlhzrved.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gticagbfrm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtnfzhvebz.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtnbuivrku.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtfafthxnk.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtzkueirff.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtzbswnvsz.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtazgtdusa.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtgxsvrnkn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtyqelygij.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtxvhgdomt.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtosfqhzdu.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtuqxrtpkl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ydzc1.top/Article/details/gtjbwokbph.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtrdxhlvlo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgogeutne.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtwljtrlas.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gtxzobagdn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtaoeddhhb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtrgjdccal.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtgpxftlem.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjgtjdgx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtahpziaut.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtqkhmvcig.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtwmdinvky.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtwwkymwry.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtqconapgv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtirnujrfl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gtjthoebyx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtwojbdgjn.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtbcufchdh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcqozocr.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gthxwrwzfm.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtpovrkyty.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtsmnxikog.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtiektsffo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtniaefjyd.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtbmsnbwtw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtbtgizlya.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrnkpdizf.html

H. 异常与错误处理
来源：http://dali.aibaodan.cn/Article/details/gtqgobahpk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthwrswdzf.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gtwehpbrgi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtnbkxstxh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfzwoldek.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtbjrzskiq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtqekcqnmd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtppvzqite.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtiinqhryh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtickyejeg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtwzbdhbwx.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtgowwtqrp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtbvobflnx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtaqpigeox.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqyvrzzae.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtnwqnmlzy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtmzvjnili.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtggyesjpr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtfskrnmem.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtwyfpywuk.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtavjlxopz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtqayzlhod.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccrtfsdz.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttpnpmgz.html


<!-- 参考信息 -->