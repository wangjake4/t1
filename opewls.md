代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2elukgitt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2qdhsupfo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2osolpzwj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2auwyugip.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2biyekasx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gt2cisheena.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2mcjdqtdg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2hoxwcrni.html

[E22] 字节长度与字符长度
来源：http://dali.yvedp.cn/Article/details/gt2uopuiphk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2vhjldwfo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2vzttsubh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2gucjsevr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2wbticyhu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gt2yenudusm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gt2noffasem.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsiuablj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2qrsmpxuu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zbdjgjru.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gt2zzsxhwsg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kfldcqzo.html

[F01] 读取整个文件
来源：http://dali.daxiang520.top/Article/details/gt2fntxdrkc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gt2asxpezpg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2saddadxu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2gnhsoxtz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2fudffxwm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2fwfaijma.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xylfe.cn/Article/details/gt2cjwwpgas.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2wqafxdqk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2gwjanihh.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2gvnnvabl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tianlin.xyz/Article/details/gt2pwgupuhu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2epwatrbx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2ivdxxkgw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2vfylndif.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2bfdbvtjl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xylfe.cn/Article/details/gt2azcourhf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2jelrwody.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gt2aiwrypzz.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2xzbxgrzh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gt2seoszqce.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvqbhaji.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgcymcej.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2nebgjchm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gt2yjvrlmuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gt2qcwexeqm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2ihmckqrp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2riwqrzpo.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlpqmzrb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2cusffdfk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2xnlxssld.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2kzydgbpq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2csorfsxu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2mteacpkq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2wxelauzq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2isxkpyzt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gt2oiptvyaq.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gt2nybfhxni.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gt2tndszsfn.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2svvynoud.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2itnvknzy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aywaxelb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmpnzych.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2xvjbpmlh.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2ytnjhnam.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2pdanagbx.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gt2xlkoprbq.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2hlibkrcg.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2svhjqsxk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2kkbyrtqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2xfxakkrd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2ejqcldkn.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fukkynxm.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjwhwsgc.html

C#:   File.Delete("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2evjubgyz.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2oipepbrm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhsxywmm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2pvwidkep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2cwcebhll.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcwvqvht.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2cznvalsj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2bpbsmfke.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gt2gtxlewwg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2yzxklcqa.html

[F08] 遍历目录
来源：http://dali.havefunace.top/Article/details/gt2yhuuzmoa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gt2iztzarap.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2qpuqicag.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gt2dhnqmcla.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxeagpua.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gt2oaxipcpl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gt2azvmspvi.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2yffvijml.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2mpiydhzj.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2amthjibn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2zjbliwyu.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2tzplyoia.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2cxsnwbkk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnjsjqan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2ubvxphnw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2nhmfurfc.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2dvnflwwo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daxiang520.top/Article/details/gt2rglzvgnv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2xkzbsqjf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hhlahghv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2ldhcadch.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwivfelv.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ozddzqkp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2aqobhpbr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axazmuuo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2gghvdypl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2jbagafhw.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gt2yayguvvf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2aukcqfyu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2dnljhbqf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2rzftdypc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jtssrprh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ecsbfvrz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2xqqwqtno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2xcqkcumt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gt2hijxerhw.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqkcpogs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2imdgurmq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2eckogyxh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2vtaduelf.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjndaokj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2dhobedvt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2tsyoiizr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gt2jteofxwq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vouitfgd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vgtpwxtv.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2luwlbruj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xybsdkat.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gt2dmvvajci.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gt2hspveceo.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2frpolohl.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2kyujsjgd.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2wvrrhsnc.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2fdxavmjj.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2ikvglijn.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2ufllcalu.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2hxgowuws.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2dacoqruz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2hmrhqmeb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2dhiwhurs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2lqijdhgs.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2aersdzgx.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2vhrpbxrd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gt2ndbkaugu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2resohphj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2rqljcapm.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2aznldjoa.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2xuqsfpgp.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2aiglyfpn.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gt2ennrvckc.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2vgwttjiv.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gt2yqzvphjc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2tmcrcncb.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2tjneoxht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2mknozhwu.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkdhjzkb.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2qrqxdiwy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2tlelvivx.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2pmdccxcg.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2bjqcgvrn.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2mitibdgj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2mugqxoyt.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtazsmtc.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2lbwfersb.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2jonorkrn.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxhwmkgm.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2asjymymn.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2xjbebtwn.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2uzlggzvy.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2xirlzjuc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2rgwdzjlm.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gt2dlksqabu.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2bcyhrxux.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gt2rmniqeev.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gt2opyrupnz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2kbwxlozm.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jlqapgpt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2opracaee.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2eubfljuw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2ynazwbjn.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gt2zngzvybb.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gt2bbasovxa.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gt2nnzsfzrh.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2wbkgsmjm.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gt2ckfglmrb.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2xstacqmb.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2orcsusso.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2njutnpyo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gt2xydexchv.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gt2aklzsbds.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzdcnpvo.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2qwjlmwys.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2xugngxfe.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gt2vgdcrcog.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gt2nnjrmsng.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cxlnltef.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2tenqhofb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2psrbqnuf.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gt2dodvhevv.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2hnivzcuq.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gt2vvxjqttg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2zbdfzngp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2xybitded.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2gjutvyzx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzntadmn.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2lqspbwki.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gt2njmuhoqk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gt2lnpgplwb.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2tpzsoofr.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gt2pynrdmwd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gt2nvkjeyck.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2fludqbxi.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2ammbskhc.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfrryrxy.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2ctwiduxn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znreotvh.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2imhepved.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gt2cggkvhep.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2egtadost.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2kpcxlgdp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdvqafbr.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fuczkgiu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zbgicaqi.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zjtfhfvs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2odpuxflf.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2oveiifoo.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgguapfs.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2qwwkhhhd.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2hwyebfkf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2kgynkkux.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2zxmpchqf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2odgpcbfe.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2ymuybemu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2vmutlpcu.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2jomfxyaq.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2slbclwxi.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gt2wglsgrsp.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gt2oodomqvn.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2bcbfnxwe.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2wnwbisoa.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2njckerqi.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2tjsdtfin.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gt2hgidybtq.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gt2nkdnfofi.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2abbdttuo.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gt2kettvpnx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gt2fmyxewfx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gt2wjjmgivx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2inqtsmhe.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2plmclxns.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnmtgnfs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2utbpxicu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gt2ifateqky.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2mtowfzwf.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2lecjfreq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gt2enkohcdp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2cgpyhpwm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2acgpdytz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrnqrnal.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2vbhjkioq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2ibwmquyg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2xrletbgw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlgtinv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nrycezon.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2buhjqrru.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2gupkgdyn.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2rjxrxdym.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2igbvjiva.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2goqybzdf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpotkxjs.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bintvusd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2gfebsjnx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2wukiynsl.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2nqjvvnih.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cgdazgck.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2cxgswxcf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2wjqzeyyk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2yuuyqljl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2xhlghtbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxmycgwq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2yivczwib.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gt2zetjzgmd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gt2nbnwecjl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2wmoqsxvs.html

[H02] finally / ensure 收尾
来源：http://dali.kuanghao11.cn/Article/details/gt2urgmskvq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gt2xvhrgcym.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2rnmaekgz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2cttnivzx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2zqchbcge.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqttijxq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gt2bwdvannc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiechpqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2atyfkcww.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gt2btunwurf.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2kclptnre.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbpzrqne.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2ddbbizzo.html


<!-- 参考信息 -->