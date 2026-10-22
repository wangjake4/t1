代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2cnlyqdak.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2uwcsqzjx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gt2nmaqhtip.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2wlwkgtud.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlrozfcu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gt2xoewinfs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2rkxpqghj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2syfreziw.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppazdxgq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2lhawfzvu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2desbinrw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2uazjqgsf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2stzoirtk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2qiwqqbgg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2qkhspzry.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2hgggbwvl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2wngkzprw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2woqooglb.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gt2cmljctbu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dczckwls.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2lnyoedsi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkjjdxem.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2eckzbkvb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gt2tozgtzak.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2nmkbzlvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2mzbwaetg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2emxusxmq.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2lupyzbbp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2itcrqchw.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gt2pgiqxpol.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2muhmndju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gt2bkgqkbac.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2twaecvuz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2feefhxgf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrcjgnnv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gt2mmzqnney.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gt2feazrdsx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2lyoembfc.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gt2vfitjzjx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gt2lsekfefy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2hxrsnbyw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2ognolgds.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmjautev.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2iczxrmgi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pycfn.com/Article/details/gt2vbzecnmp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2gfdqhgns.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2ottawdvc.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2wnkvqxla.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.andypj.xyz/Article/details/gt2hhuugqxk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2ntdxrtqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gt2rfvnqwdv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2vtymeszz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gt2syogvbjm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2evjafcbw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqnjgrv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2evvlghbj.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2mcaydhnx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pphvffuf.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2unsyfafk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2yuqbvpmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2okvtwigk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2drhyqnvg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tohklxgq.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkgugihf.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ehzdqcas.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2nwhnhjyx.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ffpejxqg.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ikgpsylh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2aubcsqkg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnuehbsk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2yyhygygh.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2qpkeonjr.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zejymazj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjbxkvpd.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2iulxbxrr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2idpihqzk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2jzcdcqlc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2tirnpmux.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2udibdgtk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2htuiltmg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2frpymnnu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gt2tlfxzmhc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2uajvmfok.html

[F08] 遍历目录
来源：http://dali.chenzaomai.com/Article/details/gt2ipxdkyja.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2njdmjujg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gt2djiisbut.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2lhdqatvt.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuflmasg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2lcocjmlf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gt2epqgbnvo.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2ybsfsbaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2qmvhxyhj.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gt2onpdhobn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cptlgbgx.html

PHP:  filesize("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2gnmcdfmr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnjujafw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2rfurizuu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2wselovbo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2owbcbawq.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2wtgchwll.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2rmsdnife.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.quarkkingdee.top/Article/details/gt2voefgvsk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ibekfpeq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2upzkuyji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eumdylai.html

TS:   path.extname("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2bxelrbnr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2vkfsmcbg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2qmulbidq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2npvyekvt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgatsbet.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2cvgdlrdl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2trfojehl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2wfpdqqjn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gvsejpsa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fknzhiua.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2wkmflgfp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2zvwvpebp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dvousmfs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2yazxyxmw.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gt2bdeexrmi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gt2xwbxhiuo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gt2elqdiybu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gt2wrriglzz.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gt2tlidkaxz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gt2eozcmwma.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gt2ayxgncgk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqgtxacf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnegccbj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2twjypqun.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2affidnrp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mmijqlio.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyqtkolw.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2owfnocwm.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2esahhhzx.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ixoyswqh.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2qtjvrafu.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2bizbtpuk.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2hnwhrczz.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2qujjroky.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2hslmpdbp.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2wxndzkow.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gt2mzhyrdjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2ggwbksre.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2stxhygtk.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2jlytrsta.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2jltyvpbk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2qyaueqpo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gt2lpnrkaox.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2rnvcqard.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2wyjfggec.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2qmawvmmc.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2aoumkmeg.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2ysxcnhre.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mktwxfcb.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzcfuzow.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gt2ijmxlvio.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2bdykdamc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2nrkaiskf.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2kzwtiyeq.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2xyiviabx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2csrkfwsy.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2lyqinehj.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2wczudwjz.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rhibcrvc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmzptyw.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2ehqurdlw.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2sbaoxrls.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmqctgi.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2aqjfbufb.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2gsfkhcqw.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2cuujfxwu.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2dokrvaxw.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbcisbhq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2yuomartl.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2xkgvxcfi.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gt2dzafmdbk.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gt2hakjdcpt.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2bcklovve.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2qcnvhzcc.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2hgloipbj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2xornzmrd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2zjojwvcp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dashuyun.cn/Article/details/gt2ifwvpiyb.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2adsplhst.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gt2ntueqszf.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gt2fdfyhrdt.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gt2usojfmhk.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gt2ldsbihyn.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2aachmvfu.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2iloluctt.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwpyvbjt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2dbmcbkjd.html

Ruby: super
来源：http://dali.gogol.net.cn/Article/details/gt2pkuvnsum.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gt2gpipupte.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2bvwxjnli.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnjeuqfc.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2bldtckjy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tasqdxqr.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ofkehati.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zmsoyjyd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2ipxxbbud.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2pcqyxovd.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2ectuoljn.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqmizwyw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2mrjondcv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2llbqfysi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2wqmiqzxv.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gt2fanlijrz.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2msnlfmng.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gt2wbrfycff.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2zrdaamiy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgdkrred.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2hwmtpamy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogtzdbrl.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2edxnemza.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2bflzihjy.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2ljdielyb.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2gewhrvwp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gt2mqtfwmbv.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2rgmlqhew.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2yenbnizc.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2nkglptuz.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldajpkgl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cmjjdjjj.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpnkklok.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2otrojkbf.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2vkhcsdys.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqxskvby.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gt2eqdvgpwt.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gt2htjjigiz.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2ckzhocvn.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2tdnufokk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rumxkttz.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2jmiaxytc.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2dzlqfvbr.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2sbckbdhd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjnftzlt.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2lebwpaqu.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2fsakksyb.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqplhtmp.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2qifxqrxi.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2iwpfumxv.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2kgpmvrzc.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2baxntpuh.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2rcemofmt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gt2fuglzcsl.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmabykwc.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2wlmvdhxq.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2yoeqomns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2cscirlus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gt2wxlacscz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2girdqaaq.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2oizmhyby.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2ltypgscc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gt2spfnjxrq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2qbydhxyi.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2sfhyxcgf.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2paucbamr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2rvzoqnjn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxhjgmei.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2teowirvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ashckqnp.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2wcwxkvfl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gt2xttwvfhb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gt2fqpaclod.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2rusrdzyn.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2jvfnvvob.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gt2tctqcztu.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oudjicgu.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2qjfvulpr.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2sdobzhyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gt2zskxihov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gt2obdvakdw.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2ziqfkcgq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gt2lgozxgzu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gmjqpoli.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmfwtgtz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fpljjirs.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2jhinlbkl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gt2rwjmwlsf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktkfdvbo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mdmzglvc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2ibhcubtj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gt2htupbbij.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gt2gduejqyi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gt2hwqypwvu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gt2fdpweamx.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gt2ifuqgebz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2pefzwrqx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2kwtopflr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2kxzhqxyg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2cjngqofx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mvnqveir.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2mxsnhdly.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmpzpvgo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjcubddw.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2rtnmgfjq.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2aiywpjva.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2axgvsezh.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwlaxxad.html


<!-- 参考信息 -->