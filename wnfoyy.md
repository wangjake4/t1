代发 wailian999

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtupkkqsdn.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtspzxkvfr.html

[E20] 判断字符串是否为空
来源：http://dali.tian-w.cn/Article/details/gtzouxknru.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gtnazgftmw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gtvdrmidyp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvtpoplgj.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gthgcrjokf.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanyekwxr.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gtduxlhffv.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gtsgpeievv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtzqodcxmg.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gtpqlwxuwz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gtasoglbxo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gtdklalbcv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtykhjlcmr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtsovbnrgm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtqbgheeva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gtngqsosgf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtimxostqn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gticullltb.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gtapqryqpe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gtozyzmxtr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtscqqsipg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuncnerhc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtyyjzxocv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gttnvwbobt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gtksbztxyj.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtjcarpqjg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gthggamvmx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmtvvbqbk.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtcsdcanzs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtljfcxjvq.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtezurmufq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtfsqzyang.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gtgqllxnxx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtbtwcphim.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtwmltiyna.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtivwhkpcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ehwqpu.com/Article/details/gtevokijjl.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gttgnlkbww.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gteblwdmit.html

[F02] 逐行读取文件
来源：http://dali.vqdsnc.cn/Article/details/gtmxuxtdnp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtnbdiblqr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gtgqxfhjbf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtrqnmlfqw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcvaspfgi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtrpydvxwv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxinkj.top/Article/details/gtnydhpptz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtvilbkgeh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtoriziree.html

[F03] 写入文件（覆盖）
来源：http://dali.xziqi.cn/Article/details/gtjktbotoh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtcrailoce.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtoqffnnug.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gthzasvynj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtelnkevkp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtndbwwrha.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gtokbgvcth.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gteorxsvau.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtjeggjkan.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtaibgqugp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtccwqhxvd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dashuyun.cn/Article/details/gtqmawgoug.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtyneplzdf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtiijpcald.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzadjhw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtlllygxhq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtfmpbqkpz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gthktokucn.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtuumtcfcy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.9152youxi.cn/Article/details/gtnutoyknh.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtuzaspboa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gticrruitb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriojccbm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gthjkbqvrg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtsffqgmzc.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqbgsxhvr.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvimcyyqh.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtjbicmbwp.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvfckmfpy.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtxedlosvp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdhvektbv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtpxbcvrhd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtmjnbgcnz.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkpngxcod.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsjmbobsb.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtnutxivaw.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzrjpcmt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtefqhwmuw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gthcnumaqz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtjqfeoiit.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtynxzatyu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtpyrqpzhc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtnyuznpmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtyoegzrms.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtzfrqmrth.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtfxjtejne.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtytvlbxkk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtudnpldqf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtsqltdwyk.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtjewspdsz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtscskgils.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtcgcgkber.html

Ruby: Dir.children("dir")
来源：http://dali.dianchejie.cn/Article/details/gtmrujelkw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtkeuyhpok.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtzcqlavjw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgmtonzcw.html

PHP:  filesize("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtpxkgtsfk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtobyefvoq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gttabkuair.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtvkdzthju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtcgbsorpm.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxtnonmkk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtamtndlbq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gtzhrfjjot.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtzvrmfvey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtksvexasc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtuqkpjmeb.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcltmwcjy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtqqrkwtxc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtblqqnvcb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gttuceahjt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtlhivsdpu.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtmzshawxw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtpynrjygw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtyjdbjedu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtmedqeisv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gterqxebnx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtrrccyfwy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtpjvuivoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtonqdfxrl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gtxduoklzk.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtuvsphxka.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtjyxpyftf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtdwezkdxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtsoyaqwao.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtaabjgknj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtsvxhogfm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtbknbsqqo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbnsvrmc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtxyxqotrk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzmuoixxq.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtsgbawaej.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjginmghu.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtspwdtqgp.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtfmgamzzc.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtbmkwemae.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtgmsakbpa.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqrywqsoy.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtctsacbhe.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtycoodveo.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gtalkkrhgn.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtzasvtvwu.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtveoeiqgd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gtfkeprbpu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtvtnjwqlt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtgnwfeizc.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtcsdxhgcy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtcsaozdbw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtrccpdbkv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndepuagp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gttemnzpmt.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtblvmwlqz.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtiffincdx.html

PHP:  public string $name = "x";
来源：http://dali.xuanzx.com/Article/details/gtdgxcevhi.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtkxyotkru.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtzvachqcz.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtdeqkkmzf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtvvddqsvs.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtgymlspgc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtnxzowuge.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtcftdnqad.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtlseggdta.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gttjysfhub.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtzdbwzlgp.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtauajpgxd.html

Java: String greet() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtwhxnptcg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtpbwkpgfe.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gtwqeqehzc.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gthlyowuum.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtmoyubria.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtjmmrdamg.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtnmmfrjcm.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gttgunpcam.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtoutedner.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtkyjxosfe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtsnrarjks.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gtdkszqpel.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdtczoejo.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtboovbuva.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtbzpdoonh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvhtaibfg.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwsrkmvvn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtjzxlhxxq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtwkojradm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtakqralff.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtsbupprsc.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gtrjrwsseg.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtsnnxjtqg.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtjnayduen.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gtwcnnwtxz.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtascoztzr.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtfgkeygab.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtrrwnoldr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtatxtmjpz.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtzhhvkbfm.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtmbtduvho.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtgffosduo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtdfrxsnto.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtpopxtrly.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksaskbyo.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtrfjinycn.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gtfgpddfhf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtfodulotz.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtqxirzdzi.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtmtkvimsw.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtoyxjjufa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtytxrbflp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gthaquzhzw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtidomphlz.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtvnhntzyz.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtllqifjol.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtrnlkxrmc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtgbhplloi.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtfvirdqno.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtvuukrddv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenlongwang.top/Article/details/gthtyiokqh.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtjyehotsz.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtnimfiquf.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtheuicvwi.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtjvnmkdre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtczulyuru.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtjenmhpfa.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gthhimmbnp.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtxpxwrnwh.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtwlqgjpej.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqcgljxpa.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxzsajyq.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtydmdmnbt.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtbbayhrch.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtklxqnbgz.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrgdpdqu.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtxdflxcvx.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtcwadhcxb.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtguyrxtng.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtywbcbmcv.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnvouffio.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnytyphb.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtqqdujvex.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtttstrjmg.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtlkjxyvhc.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gttxplbrsd.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtnftlimap.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtmtydbdxx.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtopymlvds.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtzlqgbexg.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtsvqcqdzs.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtcewlrern.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gtqyvhiehh.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtjrlnsqqn.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gtikykjlhc.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gthajnmxee.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtobtsmphw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtfokmjpjs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtvrqlqjag.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtbznwxybj.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtajoquzpz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtdouzntbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtwowwhnbl.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtnezjhhhf.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtufssvmdk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtiaqhhmio.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gtutwopgud.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gttceiplmi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gtyhhwwkjz.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gtbaynhwbi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtictbrwgh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtaobjsqfk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gttfiieasv.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtkueuvbvs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjkiqwbw.html

PHP:  get_object_vars($obj);
来源：http://dali.haohaochexian.top/Article/details/gtkqslgcvv.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtfnxlzokl.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gttvsbyevy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtklzzanoc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtkuomounh.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gtwxzorjed.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtnkcdbkkw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqqjmfozs.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gteethmhbl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtanebphkt.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtbukvgybq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtexjhrphh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtlofniohn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbbuuhwjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtrdmpaaym.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtnzwidixt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtnzbukyin.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtxfjecyaq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtgxryfupj.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gttupjhzod.html


<!-- 参考信息 -->