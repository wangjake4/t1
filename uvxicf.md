代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtlxmndune.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtooymmgmr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtlnntlhlo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtsbwlnljv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gtfdstmlyw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtsomwsyhz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258888.top/Article/details/gtvkklxmac.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtorsxgojh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppmllvzy.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwyphcrxm.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacbypkew.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrdwyaval.html

[F01] 读取整个文件
来源：http://dali.guowangkeji.top/Article/details/gtdnfekipn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtklocdmvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjuolrgq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gtpwqvhdcc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtwrorwbrs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtoqdlukyd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gthdypczwq.html

Ruby: File.read("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpmkogbmt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtfciizelz.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gthxkfxlpg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtkpullbno.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtgbahclcm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtkwbjqjkp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtplzlkhiv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gtynxemdjz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gthqrykbat.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtmkirpejv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtlkydllrw.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtbordywyb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cdnleiting.top/Article/details/gtjnwvwagd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtxojcliao.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtphkhqkxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtqsmtbdpe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtecbzqqwf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsocofer.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtgvqwpwlb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtgbczsqqx.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gtwxtgabob.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtwkdqzrzq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gthvuowjbj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtkwcivxnf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtfsmeapgg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtkekmlujn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtpqfvaxvm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtcliiusuy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqvjdwcu.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gtjiedgxls.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtqxwmrtzs.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gttipdxriy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtlrcnnpyx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbqshtwjn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gturfzucrd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtfgguhsgb.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtujagecvx.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtjdcgsmqx.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtrixpdvhd.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlgvbkxkv.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtohpsftnd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpfwtzeeu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtwjjbfcsv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtzgxfyrfi.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtreyzuesj.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gtigvjytiy.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtneouqtln.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtiydtppua.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gtsazbgjro.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtgcoznvqj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtgaajgqkq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtqpacelra.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gttizvoyut.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtvypnhimz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtpgdftcnh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtdwkswvuf.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtjqwrzivo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtbkiragfo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfaekjizx.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtzrkxxtrr.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtffyouztz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtbjhadrhq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gtzqrlgsxz.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtlskwtibx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtahtbzrsd.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtqemkdtln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtzigjowrn.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtfnsdwcoe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtabxaknen.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtsdndgfhx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtolvdztey.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtmcywrebc.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwvlphlsz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgmoqjsg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtmqiobjof.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmnmprzfb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtnstegqut.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzzjcepnp.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlmrfcyna.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtxkevocnv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfezguoyv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtrsbitqsf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqlmnwhat.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtcziwjoxf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtuappfgri.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtpypcwccu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtylldydcv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtrohigexl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtxtdemaqo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gtjjcbzxpr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtfukmsbzb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtrusfilnp.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtiqwtvhtq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtvdarfitv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtcbbfsroj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtbejddkzf.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfnyzbuh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtiozenfak.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjkrhjiq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtfpjtnlvr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gttfdbpllq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtghchajxi.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtwliyxfar.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbscqigdb.html

[G01] 定义类
来源：http://dali.jyoumei.cn/Article/details/gtweacmryn.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gthcenpuvb.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzicmtes.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtspgjnbhf.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtvrivgewh.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtjvyszfkg.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtilbltrhk.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtxlmrlanc.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpiilmzqh.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtkqjgwetw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtrnvpvjug.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtmqeclpnj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtlpihcche.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtmukzksmo.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxsylmumw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtivkppmkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gtkwmrsunf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtjsnnygiv.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexjzzlvo.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtyfunchjv.html

PHP:  public string $name = "x";
来源：http://dali.jyoumei.cn/Article/details/gthjekemoo.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtbfvdopmf.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhbhlxtc.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtdmruxlxz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.quarkkingdee.top/Article/details/gtukvjnjys.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtguxhgzrr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtggfurpaf.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtuljyrump.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtnjkoakwx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtyknmutra.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gteykxmant.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtmbnbjmoq.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkgfbhxp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtbtgbfgti.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gtkxjhvens.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtkwgnpcct.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojjizdyx.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtqfqxmamj.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdbghmgy.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtcycepfnc.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiqqrqta.html

Java: class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtlslmvwto.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gtbxmyjzvf.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gtjuytzlac.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtfyzevmxd.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtngjqqalg.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtrosvbcyq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gteqmrscdq.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtvmgwosec.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqffodfun.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gteduzremx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtnnuwysna.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtlqeaznhr.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtfzxtpqoe.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtgtjhbbbj.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtcxvkoeop.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtabwvzpwn.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gthibzmmkc.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtfgqsremw.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtfryievki.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gtabpggdxb.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gthaxchedd.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtuyfydpmz.html

[G08] 静态方法与属性
来源：http://dali.jiagoushi.top/Article/details/gtxdyicpus.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtwahqunmk.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtxzcrwpuj.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gthawyxxdp.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtexlbuytz.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gtoheimshw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtjajqqzyo.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtjxcezgrs.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtwrpewhhy.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gthnflttue.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvqnqfsn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gthbbxzctl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtrendqhph.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtpkrmxetg.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsvarftnz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtskosztea.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtexstdack.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtouxbhgoa.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtooalqjgn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gtenkistkl.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gttqegljdv.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtjjxtuupf.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gttvvrsnmj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtatksbwfm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtkukkodcp.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtlqazhyps.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtjbfwpqrc.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtkkndsevk.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtyfinfozj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtxopnainl.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gttwtzycmz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkneirivv.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduwiomgg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtrdmaoafl.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtesjokulz.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtrvyywspc.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtzhtpppjh.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtlnfolszh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtevykyvxw.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrxunqupe.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtnwwmkxsm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtscwietke.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtfjimgkxe.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gttludjkzl.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtatzkoere.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtbnzmftod.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtcrihfbgy.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtrbkmujau.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtrznpbuub.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtemkqupno.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtphpfnmci.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqogwshpl.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdrtsmcas.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gteeecctau.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gttfbhqmqt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gthjlgbpqz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtfmjdqqdz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gtglsdkhkv.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtekapswhf.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtaoipvjod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gthabamtdd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gteuidfwpa.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtegsjomxt.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtiviwplbs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtfnospfbq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtjbvfzvmh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtnivpqswb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtgurzwpaf.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtuzwwsxeg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtydttzojf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvzzrajr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gttjqohggs.html

[G16] 对象转数组 / 字典
来源：http://dali.tanke756.top/Article/details/gtwatxuvtk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtglkfzalp.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtjqycqaob.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtyqyvicxz.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtivnkjmvm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gtpineeqsv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtkcodnsun.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtixsyoiyg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtfsrfgzug.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxwpqcuga.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtsknznvrp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcwyiwklv.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtsfozyyvx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtzgrlrkpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtxdwahsvu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtidtsuilw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtiwbklfag.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gtklidxaco.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gtbwjixptn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gteygjxcfs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtghzohozk.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gtltysfsbl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtftinxspn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtjypliszu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtxzxlnqmb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwjdlbrjg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gteqsqmdhe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtengpcvbi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xylfe.cn/Article/details/gtlzqyselz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtnkzgrcxy.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtqnldvkca.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gtbstiuzci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtovozobvs.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpieezwl.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtbvbsfrkn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gttfghxavb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtyorefkcj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtpbwmdyut.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtwhxepbvw.html

[H04] 自定义异常类型
来源：http://dali.cucudq.cn/Article/details/gtcdvbirio.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtmrzsfeqi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gttltuglka.html


<!-- 参考信息 -->