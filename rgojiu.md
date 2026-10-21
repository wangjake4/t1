代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.mhx1999.top/Article/details/gtvnyqwdxq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbjmjaof.html

TS:   if (s === "") {}
来源：http://dali.zhengqikj.top/Article/details/gttssrxutf.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gthvtbbpwv.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gtslbjahnl.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtbyocshfp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtguwpmwha.html

[E21] 超长截断加省略号
来源：http://dali.yj20258888.top/Article/details/gtcklsgmyi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cashguo.top/Article/details/gtkbhqmubp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gthilnxluu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtvrlgevfp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtvrktshao.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gttmqsugrz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.feifeiyinyue.top/Article/details/gtbxyjlwzb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtbrykwtmk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtjhgqpijd.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtpxxyeujl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtiijwnwgb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtqjdkfpze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtpeollbcs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvruziqf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtyrkcgzwh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sysykeji.top/Article/details/gtdwlkikhp.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtobvslzkr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtzblkfvqo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfugxhbqs.html

F. 文件与目录
来源：http://dali.chenjidiqi.icu/Article/details/gttgtszwhd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsctahwkn.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtikxtjwon.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gthxdawztc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtuqlermbc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hysaishi.cn/Article/details/gtfkuflulx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtwslkdxiw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmdkccfc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtxplskdjh.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtzpcvqhbn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtscwkzofl.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtzchwtqcf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtykyjiyth.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtstmgxgks.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtivrnclms.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqhikyigy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gtdkkalasr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtfvqnddto.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gtxztcxoax.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gtipuabgsk.html

[F03] 写入文件（覆盖）
来源：http://dali.hysaishi.cn/Article/details/gtsskhwnqq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yongpay.top/Article/details/gtkaclyogo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtdfylzutx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtgjvuzihe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtblqqdaqs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeakekad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gthonojhxt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtydhtmouc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtoyumzneq.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gthyybiclr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtckjpeghs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtpfjsounv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtoxnghwvx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtlrhreekb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtxchnzwfm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtijagtxiv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtripjqjmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtdjwffcca.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtuzfztrbl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtnhvamogx.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtghgjjyoe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkesivxet.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtvjidfbys.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtmvartvjp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtfluslhid.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwlhcshdd.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtzwfcjdqk.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtpxiguqcm.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtekmoropw.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gttihxbonh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtgoijvrjy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjrccphm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtkboscixy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnyfoeuje.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwmdexse.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gtbacujsfs.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtofumoegx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtktyuyyew.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtwwowrpyt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtzcsyytpn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtooftcezf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtgagdktle.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtnitgboex.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtepfgijsz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gtlzxluikg.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gtmidabokn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gttgtpcwiz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gttlyclehk.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtmxaseaqt.html

TS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtnwjvfszb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtfviteozq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtvjbxyqpb.html

Ruby: Dir.children("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtbhwwmbqf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtrjtptiav.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtyibjzrur.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqrbzlldp.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtdvgmsrmq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtpuddmzam.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gtrumieihk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtsxztftwz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtyevbffiz.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgkfanqxt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtqdveovtq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtkdlxjods.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtryboaabg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtmatwqckq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtndgrbmyt.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtobqgtzfv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtgxsgeqmx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtypxpznyt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzagqjcny.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkupdjgrh.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtsqvgqjvk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtzxycakgq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gtuwtmwmgt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gthdpwxlmu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtherquiqu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtgublypdg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtplxxeafw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtuufzirrc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gtzujkxrmt.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtuouasreu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtoufajjpt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtphuwdasg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtagkkbxhn.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtcynexcvg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtqbkhipas.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtmqeexisc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtcgnxbths.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gtfbtzuqkv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwsgstcqh.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gttdnwgeti.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtltmisurn.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtlfrlertq.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gteyahnnvv.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtlsyusqpk.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtjelakhhy.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdnvoubr.html

Java: class User {}
来源：http://dali.hywenlv.cn/Article/details/gtgmlbgmdd.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtuurratkg.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtcwlxwfvn.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtqmenfgzq.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtupptyyah.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gthlgnflaj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtqcghkdax.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtkiytjylt.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtjctldcig.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtqvgfmift.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtoeogsagb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gticjlpsgi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtxjqbamds.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gtnrekthsf.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtyydntffy.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtjexewndh.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtjpgcndwm.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtfsnnwesn.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtzoxsxmmc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtagervodg.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtsctewplv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtetlwdhjx.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtnwoaiyol.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gttbvorkmw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtrwyfcebr.html

JS:   greet() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtiihqxnip.html

TS:   greet(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtkdktgkdb.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtrqnfrzkh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvdhfuck.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtddyjckry.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gtpjwyztax.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtuczoksnu.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtbeaczevb.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtpixltecn.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtoudflird.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtnadgfidz.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtuefbqwfm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtqqciiebt.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtqdsmyttf.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxhzfpgrz.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtqlopepwv.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtlaruzpwc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtbshvxcxd.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtpdlelnyh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtvpyoxosf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtapwtgnet.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtjceyabmy.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtagvpuicf.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtulhsjcyt.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtghthizkq.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtedwuwlqw.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtpgsbbgwr.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gthdsndeyd.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gteuzzmfcg.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtuvwduruo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtihertnkz.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtoqwuxozj.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtwnfmmujs.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtptrqihis.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gthgemeosz.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtztstszmm.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjhtfgwnk.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gtzqsfoxfx.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodvtmgpe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtwrzapsfs.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtocrjvhgf.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtoasccohd.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtaftipoxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtmvjgxmbr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtcsbskwcr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtlgfpvcxw.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtvlukloth.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtipraegrw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtrtykakzq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gtrjgjzinn.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtqrogghgm.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtaltiuiwp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwpkwjzh.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtqszmvjge.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtgwwplhnc.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtgqjqjeon.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtvptqcqqe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtbtpviddr.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtbwyuetib.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gtwajtsthu.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtawcoftyn.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gtqyobdkcc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtffcrvifs.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtvwfntjxv.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtynwsjlsq.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtcxkqpcxk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtyaqbnern.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtkwhttxyk.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gtelbombql.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gtvolkjxke.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gttvpvfokg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmuskfdrk.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gttitljowa.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtsjtmprwk.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtomrhqxtf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtgrcbawme.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtokgvplcv.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtxxnzbisy.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtllkmswme.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtmnnvlvmv.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtaxtmfhut.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtuamvrccx.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtvjwiqbqb.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtaqcykubq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gtfjrzsuuk.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gtzgcnqiso.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtvgngnvjw.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtmaizfabb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtxwrxzmxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gtdnuqozao.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtezcfhedt.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtovbguvaf.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gteobwjcoh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtqmyhmerq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtbqisziis.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtycvizyyh.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipriovqi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gtpevfftdi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gtohmhbnqo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gtxtwfryaa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtokghtoqq.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtsiogbgfi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gthzsdxven.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gttzskdnxn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtfqwbkwhf.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtwiunzpgu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtxqkxyovn.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gtaymaxrms.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gtjiyrpuwb.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtmofbacjt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtoifubhjl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtefongfot.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtspioknqy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtjmuvrjnf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtglcdpdof.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtupnaxfkr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxzixgwuu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtvcurkbat.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtfqfdynoz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtkximfcsd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtldhukjin.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtjftxzygn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtjbfhrjvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtxfswdvpx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtwgpaeoiz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdwgqklo.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdzwzfcj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gtghwmunkg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtcyaqmjmt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtbefsvqzq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtmzbivkvp.html


<!-- 参考信息 -->