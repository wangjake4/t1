代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gtefrkfqqd.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtudklsyur.html

Py:   s.splitlines()
来源：http://dali.daria6918.cn/Article/details/gtpuzpckws.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtqgffddcs.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtfxhvevja.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtwpzmfagn.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gtrnfoaatd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtfmqdkopf.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtauhlwfbj.html

C#:   s.Split('\n')
来源：http://dali.zhiwuduotai.top/Article/details/gtkopwdthu.html

[E20] 判断字符串是否为空
来源：http://dali.andypj.xyz/Article/details/gtmnfroogp.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtxoexkaih.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xylfe.cn/Article/details/gtfptyaqtl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtqhtvuder.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gtilhskkun.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlsyswghn.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtzhygpmpx.html

Ruby: if s.empty?
来源：http://dali.chenjidiqi.icu/Article/details/gtrxihefhl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gtzcvmtdwb.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtqkienqkf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yj20258.top/Article/details/gtoltydaza.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtmqiaysmh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtgxswwwxf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtuknirzga.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gttffrddpq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yvedp.cn/Article/details/gtbckpuvqo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtbjhvivuh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtnnkqflgg.html

[E22] 字节长度与字符长度
来源：http://dali.gaohongyu789.top/Article/details/gtotbwibmi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtsawmbmli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gtctzwlpdx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtxzhamuaa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtmbmknfcd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtrodydvzs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.snrcjt.cn/Article/details/gtnzonbevc.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gttfvgexlu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtenzylnem.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbrxyxpms.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtzewehkbs.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtstyefozk.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtpoqjmgpu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gthwqxcahv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gtwcbzhbzc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aibaodan.cn/Article/details/gtwlkmllgv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtsfeptanf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtltostbln.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtinsgqyob.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtftmunocz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtfoyepcok.html

[F02] 逐行读取文件
来源：http://dali.hnqzz.top/Article/details/gtgodrizeq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.feifeiyinyue.top/Article/details/gtrpbgoymm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtyuhmajlr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtiseexxwj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtazquwgyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gttqqishzh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gtiyvpclmk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtabgmycku.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtjtmgnamy.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtkhcpumfb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zdqjudy.top/Article/details/gtamxwkfbx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtescsoqmm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtftqizfcs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtzbxebdvh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtznibwzjc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtmlwulrhc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fengsongda.top/Article/details/gttjdjrhpz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirjpcbus.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gtmwxlqnbu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtldpivqht.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtqpbbsvzn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtcqtaqydj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtynlmuint.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtvondhqqq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtdekjigav.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.iojbl.cn/Article/details/gtpdenjcdt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtdlfdrevy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtsrlkmndl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtdisbtanc.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtoyfbggkd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlrfymhf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjsxvzgop.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtoadtsvxl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtehmylcjn.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtskntsfzs.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthtkhjesp.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyripbrtk.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttdvyycyj.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtvopvegbr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtmdtlxgny.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtqgzixrgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtfbivbdku.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgjzkwcij.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwosupmxy.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtwselzjxp.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gtatcfwrkk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtrfmqgxqr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.c1oappe.top/Article/details/gtobfdipud.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtcpfqbhrv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtmaprhotj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtbefdnggx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtofcktkig.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtoyhzswme.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtvhiohyne.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtjdcqpzqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtqwffkmts.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtuuemowqn.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtephkukhg.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtlcucubev.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtkfzsfxzh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtojyqbcew.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gtqweozpwz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtrzupjflg.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gthpchumge.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gtccdcgufs.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfjgdmrqa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtndogjliz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtxwmmbnjp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtcwoushun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtgiaxsdpf.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfszdlnly.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtbhaxgnyd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtlbfnilhs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtcbkygsab.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gthdvlzekj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gthinqmthw.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtkrioctum.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtvvktqgfx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfiwcyomu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtcmxfppwj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcowpbgdq.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gtvebttoex.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtgimsluqw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtdfcfcosn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtsobckirm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtxbvvzaxp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gthgjqmkzs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtcipukler.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnmubgxs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtaelqkjsd.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpitgdvkb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtpfgbaxxq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtmjridrrl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtbhfknpix.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldiaztpw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtzsqcpblv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtzewnvfop.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtfahrnveh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtwecoymut.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtzcrzeoxd.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtwlxwlacw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgusggicy.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gtgqudnukh.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtucysuoyd.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtninjjrri.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtybpbgnwq.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtfwqgyris.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtaxmujset.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtrrwjlhsm.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gttolhsugp.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gthnbqwcpz.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtkgzdwqui.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtaxhaqjyq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gthuyierjn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtzpkqlrna.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gterypciwk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtxvcpfwsb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtfmjoevuq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtnoitxjpu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtrehhmjge.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gthmwsoqip.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtkuoebyur.html

PHP:  public string $name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtynejnbba.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtlgincspz.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtwmqcsrmt.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gtkbowluak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtgmmzeufq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtiqhobnlk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtsmzihfkm.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtfrglcpnl.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtaqbsegxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtetieibiz.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtlclohjvp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtxehwvaof.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gthfofjqrf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtxdlutlju.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtjzerlqot.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcmlrips.html

[G05] 继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmkqemam.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtvkswenac.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtpurliztv.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteboygish.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtzoophcsz.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtkhwjaxuz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtrlfgpbxq.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtrlpbizhq.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gteiuzfutc.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtnjwameka.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgufenzy.top/Article/details/gtsqcyukyf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtlzpqeqbj.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtublkukoj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtykdivmei.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtoicqigip.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gtjmkaxhas.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrtafnhp.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzfrcskd.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtuiwxnyjp.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtuxkzqgxm.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gtvkqnjvcr.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtwwteqeof.html

TS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtjcppkhnz.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtaltumxtc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtofzpluzb.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtzeczwzai.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtnkzcfyca.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtcgbscshm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gthudfjsky.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtdqypiiiq.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtbawwxysq.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtnxnmnimg.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtalmyfvfn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtsddbznpq.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmucgxvd.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtphonenrr.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtozjdgctv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gtsluwvsvl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtmzmvxjnr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gtpfpetmfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrlxyvfqg.html

Java: interface Shape { double area(); }
来源：http://dali.yj202588.top/Article/details/gthfqawgyt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtomfquuua.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gtrsogogre.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtmumnwted.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gttjnwnvbm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gtxlckhuue.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstxzpvuy.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtieefmzqz.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtgoplayev.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtihdqiuql.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtyfdrqeik.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtgzpgijgr.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gthoxuemfb.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtkaaynbbo.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtwdzahjmw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtopczmaqe.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gttlboslne.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtxvjpgmhc.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcxisncc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtmoqxzyfd.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtodstaqdf.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gtyrgfrhtp.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtqrnpsruf.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtfztvytol.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtxssyzvna.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtudjmzlga.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtjtebnmuu.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtzvwfzrqd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtkpfxesgh.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gtcneeabpu.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtpfsopbnf.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtvgqbilkw.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtrhelafvs.html

PHP:  $u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtdrhgmjaj.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtuvtwvqmz.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtjthqvlps.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtcayoxqvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtiscubfeb.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtqejogjdl.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtvplldfiy.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gtbmimekyc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gtyyvjfryl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtasqgvmnt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gttkoobwzo.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gttxsmjwrx.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gthzuobgon.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gthmypmrwx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtybbdsgxi.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzqfhowh.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtrakmjqnd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtciazzuvq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfwpsikfq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjsuipsl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtehifiscs.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtdmstogru.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtzvsvxnex.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtchruhuln.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtciozwshb.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gtmrkdnsbh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gteqgwtgqr.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gthxcmwaan.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtzdiyweal.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtuezupshl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gtoskcaldh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gticqiwkuz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtwmhgvvan.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtjtyhjrfh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtspohdqax.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceqqmirj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgbkgjxwt.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gteukvcuww.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtslryizys.html


<!-- 参考信息 -->