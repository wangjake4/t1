代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtmobcohfw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gtgfomthss.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtktycvxtz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtvmrkuxer.html

[E22] 字节长度与字符长度
来源：http://dali.zdqjudy.top/Article/details/gtfhkhozrv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gtmfdqznmg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtjpsisipa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtfrqqsbrl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gthzeehfre.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtwkblsjgq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtvllsojuz.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtublwmywu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtobdfqnxb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtzgwzaeez.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtzjxfrqlw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbrwdqyzk.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtxelaoelp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtbogdallo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtvelwknsf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtrmaskrqd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtudvylqcg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtlmedlcdb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtrfgsadvi.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvigribuv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtwlgvzkuz.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtqztsaqik.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtdfrbtpnt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtsngrpffp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gtfnfcovxz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtvdohxlhx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtufjrbbkl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cheryme.top/Article/details/gtkyfubfxc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gtzgnaaolc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gtennpsejf.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gtuxqfqbzs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtsyrbtjdm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtwbeqmotk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtjygrlemy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gtcalsdrfs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gtoljldazh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gthpcaxyfl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtkocstscl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtrlbnenjo.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfodzdabp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtwqmswmab.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtvuheocru.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtzsolrtrq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtcoscznac.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtoeicrhpj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gtfswkgopj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gthlagissw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtepjvxcjm.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtfrclkrix.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gttecugcji.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtddfomqwf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqzmgikeh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtgwowtyif.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gthuonrqel.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtucughild.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtcbejpiax.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxeylvota.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gtxieupfcz.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtipfaqcjh.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtvjuqhtgr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtcdleesqt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtovfxulvu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtdlfrmozu.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtsnlmujed.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtzafcaisl.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtvrgtflxo.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtviuhtccu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtfkagyrym.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtfqrstbdk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutfledio.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtkynhsdyw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.meibo888.top/Article/details/gtqbwebmgi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.iojbl.cn/Article/details/gtmapftqza.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtlkrjcvuy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtespesigq.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gtmpofmsls.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjynlccdo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtmylefyrc.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gteofsqusx.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gthvbxqxbz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gttdjwxbgh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtaafxznef.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtwaqwuiqo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtwpusoprw.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprphyekg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtwxwlbrci.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtiwitvsta.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtokiohkdy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtmqicpjbt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtlralhblz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtkqrmrgvi.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtijdowgvq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gttkamgurc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtzilekges.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsxkhpqff.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtexgbdxhz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyazziavp.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gteipiqwqx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtrkxeigoe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtpooqtdkx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedgdzlmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtryrdvvpk.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gtfnhkinlh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gthgovfpzw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtwzofzmwq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtwrwxcyqj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtmydlelxx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtrbguhjnd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtfgtaljyq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtxlqsjuyi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtgibwfcyo.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtkrkwzocc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gtiajmcfhm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shangyingyoupin.top/Article/details/gtwnhsptdp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtrihuytqq.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtibimvdmb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtthxwlnre.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtmrbkhtck.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtqjansvmp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdimuxwm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsvxpekbi.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gttcbwlrdu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtjsldkkxf.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtiudvtjqs.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gtohtrueah.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtqfdepgaf.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gteqeyeqhi.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtcubwtzez.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcskxbddq.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtezuaewbn.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtqxqjevgy.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtstkpptvl.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtrywueqqg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtvtklmknq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtsmxpbfpb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtbdvchmsy.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gthopclzxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjgzpsulb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtawgjsxub.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtaeruuijn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtjhdrryhv.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gtyhltelts.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtyxtsdbyx.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtyzqxeihg.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtuihkozgm.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtgfhaoutc.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtlgpfdcur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtysfpennh.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtwqpxkoyh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gtdjkgljse.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvtmtbdr.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtmqlpwosn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtwthbabur.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtelxstgak.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqalzwkvc.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtefxyzyin.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtlndxidfd.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gtyhvchmqb.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtmkyvnfyf.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqjbwraz.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gtpvvbmirj.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtelkjxsny.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtiwwbxuyf.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtnptffywo.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtqgppboov.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtxaapqavp.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gtyoeigamm.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gthfvgxjbs.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtkoptobsz.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtakefdhsl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtjsldmgsp.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyedaizw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtnarcmhxd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtiwfquqex.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtqemtrvqk.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtjyzkzojl.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gtftmkvwew.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtkrqesemr.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtalrvustl.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gthigbcjmg.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtycorohto.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtnuwwfkfz.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtuafgsayf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkzfbhph.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gttiueltyn.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtqvuowzdn.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspjldhvb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtwhaylgxt.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtfuafrviq.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbrvhzxkg.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtkmfxybvw.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtwjwafvop.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtezmubzou.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtyrdodfag.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gtyoufyael.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtdhcjjcfn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtvcvpugjy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmcmlvidz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtwnonmhge.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gtxinbvboc.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitsjvzxk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtaycfasve.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gthmcqkqan.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtcledezaz.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtwgipxwwd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtkbzzgvuq.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtgkqqxbof.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtlyuytooc.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtqojzlgrc.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtgdyvtstw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtkopqmjbm.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtkeclvwvd.html

C#:   public / protected / private / internal
来源：http://dali.redwolf501.top/Article/details/gtdhreolrj.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtoutatonm.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtbtbjecld.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtcxlyluud.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtsnofllxa.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtvbfvlwgf.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtlraxvbvt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtgepvmgaw.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaliegonw.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtbgulpbho.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtunseziro.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtindbnpfa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtnejmozyw.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcdungnnb.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtjepmlvic.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtcmbaahfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtddywbxfe.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtjloemdxx.html

C#:   public override string ToString() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtexekrqef.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gtcggzpmrc.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtcvtrsbgz.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttzqstmel.html

JS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtaettalbt.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtpfoiduby.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtahmyhdmw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gtmregqmai.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtjjmiaflz.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gthwelzrss.html

[G14] 数据类 / record
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnjtchwd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjavbafe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtjbgrayud.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gtxpglwoyk.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gttfiofkri.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtssohukfb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gttmauinta.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtyuarzaue.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtqswhpvjp.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtssfdpfch.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtenmftcpi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtcqfxqnwz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yvedp.cn/Article/details/gtceucpafl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtkvijuksd.html

Java: enum Color { RED, GREEN }
来源：http://dali.hywenlv.cn/Article/details/gtzcpnmkid.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtwgzhtzbg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtjstpgclv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gticzvrsdp.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtjfdwatow.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtqujcoqct.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtcoebhvng.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gttopohsbj.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtqlgbjhty.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtxahexmrj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuxming.cn/Article/details/gtdhkbmcui.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtjzvidgvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtgpehbjss.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkulpsvq.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gtwhksrawt.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwdqwvze.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gthvdgktek.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbbzadtq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtdxakuquw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gthrmdrmqt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gttskcgdpa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtxrkecazy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gthofioezw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtnefktpem.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtrbivcepa.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtjkdmfpfh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtdlnkusxb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtimdhqtpi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtcjzagoyo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtfsigczlt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkwwxztxa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gttlbycbba.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtabghwtqw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtuvnavgnm.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gtxwiknvhs.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtflxuozad.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtdjtztpyy.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtpaxnihit.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtgdepykqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtpwgucrek.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtgcwzcarl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtbshwmhzv.html


<!-- 参考信息 -->