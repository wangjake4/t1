代发 wailian999

Ruby: s.lines
来源：http://dali.cqqwz.cn/Article/details/gtvjdvaidj.html

C#:   s.Split('\n')
来源：http://dali.hammf.cn/Article/details/gtplmbjwtx.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxwwnvju.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtwnrjoxwu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gthbhdjlgj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gtafeercjc.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtqzizlije.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtxdbvlbjb.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gtcomfffbh.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtqjionzms.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gtwxlnbtlp.html

[E21] 超长截断加省略号
来源：http://dali.gzhubu.top/Article/details/gtespliyen.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtjfqgldds.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtvufnvbmk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtiuiqrtcf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtkqdwgcrs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtyolotosn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ehwqpu.com/Article/details/gtqsmjenrq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtbcxrplor.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtnjgdmrzt.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtnbxrorbc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtcxwyvwyu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gttsjlsjas.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtqymlzpmp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtqofplahi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtdvpdefgm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtapzbabxd.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtfkilryzn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtrnwyyczs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtfbjgoexk.html

F. 文件与目录
来源：http://dali.jqgufenzy.top/Article/details/gtqvfgltlv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtupqnjfya.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gthakxrsuq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtmdinohgk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtphjqrsom.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gttlzkhpjv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gtatdiqcar.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcveivfqi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gtvbyrduqf.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzuvbwwvp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtruewspxc.html

[F02] 逐行读取文件
来源：http://dali.zhengqikj.top/Article/details/gtgbdqaila.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gtqgbnbgpw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtfcydjbpf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtliugkslz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtsvhmmsms.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfypdiax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtemoxmuxi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.9152youxi.cn/Article/details/gtccgfsdeb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gtcbazohah.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gtcunafrza.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtzlzgttzj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gtyfawdyjl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtxfvkztge.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtlhayiajt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtjckrjamz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtuarigcrc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gtxhsctjag.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtapggazck.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtebursnba.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gthfiukggu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtosuquugj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtmpxoojho.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gttdrxtlzg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtigaamubv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtoldnaztc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtrohrfpgt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtykaukpuk.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtsuynazvp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtsacunoub.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtlqxqatgo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkjgltbyv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtssazcdqq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtkhclbngi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gtrexemskw.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsnguprou.html

C#:   File.Exists("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtztonohxo.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gthfjjngiu.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtomqjdiaw.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtervpjziw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtommmtrdk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmyxpjrhp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtxafrpuvu.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtzekifeki.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtntsrxwvg.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtwnqlabjt.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtllrikogb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtmffutrdr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtagxvxdnl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtetpldnxe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gtgmsfxcmc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gttfskgnuq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtikigtlyn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtijlywtjv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtdatuetbr.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyafvmap.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtjbukbaff.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gtrusmxiis.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtsotwkava.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhnnacgi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtrylfodnc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtlvlokfxk.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtjshxdquy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtrkguibvj.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipvuhkwm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtaryzfpnz.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmnrjbhil.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gtijgrymhy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtqocjbbtj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiioezkl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gteuiwbkes.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtybhtxnjc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtvbhznzws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtmnvzfext.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrijqqloo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtfquuafvw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqcbvugn.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqwkgpvw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtkqlkgngy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtqpfwrvgl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxdrwgsy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgmyekpqj.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryfsetve.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtlunspyuf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtfbngdxpe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfdzowvtr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gttoecowsk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gthhtyyuzr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtujibznyx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrjegciay.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtxulfxull.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtrsmabdlt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jiagoushi.top/Article/details/gtjuejavjf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gtynkzxbdr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtzkeophvw.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gtfdwjyvms.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtllxsfmfe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucmjiipl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtwkuyllqj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtyeqxxokf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdgjtzcto.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gttdmygqvg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthummhzxe.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtytfythry.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtdkfqqnit.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtjpxqkska.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtzytaqqiu.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtcolcimqj.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtqoxtrsqa.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gtnbwusbhd.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtoxhpxssq.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtdllyubms.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtggjszaky.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtrksldjpx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtpaatxbbd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtodnvrxir.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtidbgfxsm.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzrrfuwyr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtatobfsku.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gtjfesaino.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gtwioforse.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtjqrhyfme.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtxqxksigx.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gteqwktdzu.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtcxqexhgw.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtmzqetjhz.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtgmjmyrnm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gtwlkfxgne.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gttdaplgvx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtrzbnnkgg.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gthqrsvfsk.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gthepdwjdz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gthieojmgy.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtisyiwmix.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtgauuacnc.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtkmmuqafg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gthlbbkfax.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gttzuggcqo.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtfvooodxv.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtoeeudjvr.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkxciffe.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtuyqeasep.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtnqxzccmc.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtipkgojei.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtvuzrmeof.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtvoxwmnxf.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtthizwewt.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtvktjfexu.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtbjwpgrxs.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtuafhlrpl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdgavdxtt.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtcesxlytx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtnwjnjmuf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtqhedzays.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtiunbtwhs.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtjhnqrtpu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtpobynysi.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gthaqcmonn.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gttninvaey.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuwpuzypj.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtnvtetsac.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtwssqncfa.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtpqxzyueu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gtitmqbuvq.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtgmiadced.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewhaqmsg.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gtjdcwbkdh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthckvkasi.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtpdhyjqst.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gtlfnkxvrl.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtvqefudyd.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtkxweajcz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gtelisavwj.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gthwxjnghs.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwwbdjrq.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtkxazmpeu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gtzgmcxljt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gttiewyxgi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gteikgiacv.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtsesknfzz.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gttqbtizhn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtyjptscnh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtykddiciv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gthwehwltr.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gtndoaowel.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtjdhjgtbj.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtcxcikfux.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtlbujlwea.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtqthcptxv.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gthlazqamg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gthebkxfcg.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtztvjopir.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtgfdvmlmr.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtxgmhgfwu.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gthgwqdikt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtieywhvej.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtucmkpgev.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtfbocukiz.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtmewneipy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtgwrddppu.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtjoptazav.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtxcwhpajq.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gttmfyvzun.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtkdfqzehs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtoxqvhzqf.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtvicpqosz.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtwwjhdmdn.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtlkkdvoqg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtgaglinuc.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gtkgqvjolg.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtikijalka.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtudjfwjuu.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtryuejenu.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtfmhucmoh.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gthctrasxc.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtzmnvaava.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gthnijgcvf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtvrvmkxzn.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gthvruzxza.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtpldfcxks.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtvafrjdsr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gtamzgssne.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtliqeohzg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gtbrhxztdf.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtqaezoido.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtiiusqeta.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtbinvosht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtngozjeyq.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gtbmaikvgy.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gtxongkjqh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtjaqdnsfy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gthsgjelmc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gtlveyjkyg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxseptqz.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtzlfzfbsk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtqbwysckb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtmanrinaa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtnnxmkuxx.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtkcuddjee.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fengsongda.top/Article/details/gtroqwbuyj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhiwuduotai.top/Article/details/gteudhjkly.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtpgwplqwa.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtvkmvxoqr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtxmzfmavn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtaxfovtwa.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtsxruiplx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtbxrlbdkx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcjsojpra.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtacanppbe.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjtiohith.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtytlqmtid.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtgvtzdoxv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtwwpyopcl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfyuzbya.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gttukhraqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gthjbqunox.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gtrodefshg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtfynnqjpa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gtclhgsjam.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtkqypqztd.html


<!-- 参考信息 -->