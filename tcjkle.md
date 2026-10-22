代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2czvhfogy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuanzhike.top/Article/details/gt2ufcrxvbl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqqbnmgu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2wuvgsbfb.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gt2qzbifbfn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tian-w.cn/Article/details/gt2fccdisqg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2ljaxvcpv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2qrddikqf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2ojtmlxzh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jiuiqihg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gt2svuolqlx.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2zhhsrqst.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2vmlpdvye.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bpxanbfv.html

F. 文件与目录
来源：http://dali.bjfxy.top/Article/details/gt2abzihqab.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2unewkqaj.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2aavkmivp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigufen.top/Article/details/gt2pvdcuifi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2gxkidtql.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gt2cuosajka.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2nytaufme.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2hdqdpsbd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gt2rqnylugn.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2txahfqjq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2fnihbjqk.html

[F02] 逐行读取文件
来源：http://dali.daria6918.cn/Article/details/gt2ucehfuxz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gt2dxhzharb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2povlvjon.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2llnjphuy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2dfedooeg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2igfkbzxi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuanzx.com/Article/details/gt2ayfzcbqz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhoulong.xyz/Article/details/gt2njmemzli.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2cmrphubn.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gt2vibdekdo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2rnssripn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2oaribuwy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2gvftprxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2mikmkrzz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gt2hqthrgfa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pumuwsfp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gt2drlezhqn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2oevbopyu.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2xvbabcmo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2jifffpem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gt2hunjpokk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2apgclxaz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2hsyxxkms.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gt2qaagytqe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2nwkexaxy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.0kj1m.cn/Article/details/gt2tfogrira.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gt2cmdmiywt.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gt2tymwedgq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zdqjudy.top/Article/details/gt2fnmsfynf.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gt2hivlkdsi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2aivvqibv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2exzgnjdc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2wyvmjznm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2yjgaoqef.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2epsetzdf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2cxhvblyq.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gt2pyltphmp.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2nkuuzgsb.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2tmlcxkil.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2bedmpgfc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2fnbgstrv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2owetmmnv.html

Go:   os.Remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2teunyjym.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zmjbzigg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfztgqqi.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gt2tejmtaic.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2dpwytysd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258888.top/Article/details/gt2enelbozl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2ifmzhjhd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnhlefao.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gt2maavnqwk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gt2rsyfxdiu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2zpfcgdml.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gt2acujzjzl.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2jkwxrihr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gt2rlmbslyb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gt2miparble.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2palihncj.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2aemjaeij.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gt2ylzjraut.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2zbbhdbdv.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcdyjccd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2jomtucux.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gt2kweztkhf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clzwympt.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2xoifohks.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2ezvuthdw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2ugmvscrx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gt2aylrwpfz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2zxivkjoc.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2lxyfceot.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gt2xzegwbkh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2hrmktwbi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2jfpqkjdl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2aphmwbwc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2irclikgu.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2cqpghgcq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jcreltdj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vnuytvug.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tahleudb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2dhykjuhj.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gt2cztjmgzw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2nsdrpeqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2xflvaprv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ioilhfam.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ocirjybk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2pywennmz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2bcgrjlyv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jdvfmpnk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gt2xqysqqpg.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhaxbohd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gt2hcnrvfhb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2bfnlehqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gt2xuotthse.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gt2touclcbk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gt2sqdpyrwv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2zzqlzfpd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gt2vixmslrr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gt2poehcuzf.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vteegsgc.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2roinhkjo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2uuexrpfl.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izhfsjpw.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gt2braegsfj.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gt2dokoufnk.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2cukelgrz.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2uqxwnxhf.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gt2ixjfhdpm.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gt2svpuslyk.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2usdtjyxw.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2nmokdixg.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2ejosoxhf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntlhrqgv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gt2hacfwuzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2evhwkmjc.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gt2ismnlikv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2zhphfnpp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gt2yabyuktq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gt2efygaymp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2tjqgmzaw.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2asiwhibv.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2pfiidlnq.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2ufpadwof.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2zfpaxitz.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2vgylyjhs.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2rtmbkoeo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2sodvvrxo.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2mhljuuzi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gt2wnorhbvr.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gt2kwjeqmpm.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2aozjqlxf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzahbmzx.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2liqzwtgb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2enfehfap.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2gqkylzoo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2mraccfoo.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2cukzxauo.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gt2ewadvnat.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2vhzdazvo.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gt2kmuuaowa.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2shrkomtz.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2cdphwirj.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuewswne.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2czvqaior.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2mrzsuils.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gt2gwislnhc.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2juyvcnlw.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gt2gntmcytc.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gt2akqenkmi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2lyjilmje.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2okwqwjxw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2rnpqnxme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mlekbaqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2ngptbxxh.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gt2idmlnbvc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2ntmfqcmm.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gt2jizcmhgb.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2shkzvnaq.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2eucjknuc.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2mslmppfb.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2jfhxrmje.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2rvqfrnhd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2oelpecdd.html

Ruby: super
来源：http://dali.redwolf501.top/Article/details/gt2jhxbchua.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gt2aaplyefh.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2jgchfxnz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2gpcmvaut.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2mmrawjdm.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2imqktszu.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2pqcyyaqh.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2bmyiavjl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2peuwjdcf.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gt2klxpoxqw.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnnuyjxl.html

[G09] 接口 / 抽象类
来源：http://dali.hnqzz.top/Article/details/gt2jhpaoqib.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2nbdovqgk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fezulpxi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2osomwmaz.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gt2faxpxexa.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2udqhcygg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrefewwp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpkhoiwz.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2brsybqwg.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqzfuuky.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2nkhpuymc.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2fmbpcdok.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdokdzts.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2whhlcrzd.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gt2zumxzihj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gt2xgdblwfw.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2bigdijmj.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2yaoqrvkh.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2ycurrldr.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2xketsxfe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2mrcnguyr.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2genswuru.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2rkfyxupv.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2fohnfqpx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2derbfjpx.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2sokfkxkq.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gt2ohakaxfp.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2nafgpiyo.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2jmatrnie.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2qpmqdhqs.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2jcdtmsuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2ioiuwliy.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2qoudnphw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2ppbwozxt.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2kxbfaqku.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2pxknmymn.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gt2vnjleygx.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvdxlcsl.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2wxjzwuob.html

JS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2rwoeshab.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2orobxdaw.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2wmtztwif.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gt2vbvzltpj.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gt2qrrighaa.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2kwfkoqot.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2mndgfqns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2hurnyzug.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2lpddpxgd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gt2zvtyifdp.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gt2wpiwvrky.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjljmbrx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2wqqbplea.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2ikvebipf.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2wozwoswp.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2kmgapyrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gt2avjphdoq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gt2rcexhdxu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gt2nntxwgsz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2ofkzqfhe.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gt2grlaxgrz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2skyvzbxn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gt2akjupjcc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2nqyvmibw.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2lndrvwaa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2ehunarbc.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258888.top/Article/details/gt2rlvjfhss.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mxeguvgy.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2jybpkoee.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2iufxeoer.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2acnneteu.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2lezzfjde.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2upadskho.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ruylmjrx.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2nxshxgpv.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqjvyiwf.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2koyuldad.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2ugbldarv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ufcglplb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgumtefw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cikgtmxp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gt2boomrxcb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gt2heylwnnb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2lsxvpynn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hdhlgrlp.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2jsiwlgvq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.redwolf501.top/Article/details/gt2efvlfnre.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2wmxrajwd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2lxitkneb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2yszlgsxv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wutfjdkj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2gqrqqudg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gt2pkzsjehf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2jbngpmbg.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gt2uxrvgdqt.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gt2ampldefn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2lbvhqmca.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2llybpuze.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2umdjjctw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2dlhkotcy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2lxqhdyif.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2pssqsoyz.html


<!-- 参考信息 -->