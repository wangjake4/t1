代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gt2vnnhtlai.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2deqnytcl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2kzstwdok.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2oiegiihj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2jiackhnx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2mconqzeo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbxnaaec.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2anxxhzry.html

[E22] 字节长度与字符长度
来源：http://dali.zycfv.cn/Article/details/gt2urmjdhft.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htvrsceq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2vrvbdcna.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2unrpxoxa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyzmsraq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2ovgjuipf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.fengsongda.top/Article/details/gt2iiqulgtz.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2xgvxtzue.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2xezlmztu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2jsfbuyyl.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqmuuigo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2swucvpuo.html

[F01] 读取整个文件
来源：http://dali.quarkkingdee.top/Article/details/gt2pagkjdao.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gt2rmvjaidx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2sicytlla.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fengsongda.top/Article/details/gt2hqugrcuy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2oocbaena.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2dmcncjee.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gt2uwiokqyf.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytsucpjk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogcvdvnn.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gt2cgyhaujp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gt2vqjqvxkz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2vuohhqau.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgovxoml.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ggguskic.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gt2umodljws.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gt2exsgojiy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gt2upnxjeyk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gt2itrzhbfz.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gt2enfkqhve.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2lnmvzpti.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2hjqrmoeg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2vulozyyr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2ejxjnfuj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gt2jkaiznvm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2ecbnqtdr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2phyrqsta.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2dfkmzive.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2bkvuogjp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2pvwldmkg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2rzpypcgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2ertkbeld.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2zvyphyhj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdoolpft.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2cmwnzytn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2ucrlksjc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2ctzustws.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2acmonmaw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gt2ciacmydt.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2idwyyivq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2jodrzftj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2msvewjix.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfjbusko.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gt2dncmzsue.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ogyfyzlb.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2vcewyroo.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2ujujhlpu.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2vbvmrdss.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2sllltmof.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2ojrraztj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2nqbxgkkq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuaemhsj.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2okyogqes.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gxetrlts.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2xeuykgbk.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gt2xwmvlynr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2evvpzczs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2naejljrg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2meftifjs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2vmejttik.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2uqddeyjf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbpswjno.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2yrlxshyx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gt2rwnwwfko.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2jilqhbnc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gt2cegkjnwq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcnuhdzs.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2ebmuiupt.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2rhqrnwee.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2yweodbuc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2tvccsdcr.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258.top/Article/details/gt2aszoiykw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jianghu66.top/Article/details/gt2nwtqshnk.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gt2bzpixxkn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2eitouhxo.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2tawwukin.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2krxzdygh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2zqqzfdnb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxeqjvnj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psqmuhtm.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ktzdbjsn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2pebvikln.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufdznofj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2imegjplh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gt2seikzxvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2pkbvyfpt.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2pciuouhd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2kibfctzb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xmwywypm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2adljafrs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2slronqyg.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2nahlatci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xqzxrlbf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2xejwyrij.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2rhwrqjtb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2pefqjhok.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2rlbqlnda.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2finzkhis.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2xcjlzima.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pshblthu.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gt2brzfeyhc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmvgievh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gt2jetoxuqg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gt2capoxvdw.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2erjwbzlw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2vjqkbjcy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtmnpbyl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gt2tlnsejba.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2taxmbypu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ncuxcqvk.html

G. 面向对象
来源：http://dali.zhoulong.xyz/Article/details/gt2lyajqhuu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gsjxtfqq.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2abrazynf.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gt2xczgdfxx.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gt2ymisqdcn.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qhsivetx.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2fcoaatrb.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2hjmzdxti.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2eaopbxvj.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2jvczumih.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhwozdnp.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2mbytvhzz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2toscydwg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2iovpctin.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2oldkrwyi.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gt2ibhdblap.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqqvbju.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gt2ysstagtl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egkioffs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2yodcwvfh.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gt2nwtmiizy.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uewuqctg.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2ydsuykrx.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xsfpaews.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2nklyuscv.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrivwmuh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2gfwnuvqv.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2liqqkbrv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2tuxcvirn.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2clxfxxcr.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2jspxggei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2mhmxnunj.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2ierdslno.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwsechlz.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2uwmzeotr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2ssltlbay.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2zaectoij.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2iykvxsry.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2ddtrwtby.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihuixbjz.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2cvpewwgi.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2nzhxgcsa.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2xrbfgyfv.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2wlgbildd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2fgstmtil.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2ooadfadq.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2ehjpelut.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2lqewxnwr.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2tvnghnte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2uwwkfpdw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2puewvnwp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2bysihtvp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ojzrugns.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2nmstudza.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmstdfqv.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gt2ksqakamq.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2tviptflq.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2lalbsaho.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2hvakdqki.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spnacnap.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2ccbbdtwz.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2wjjaxyem.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gogol.net.cn/Article/details/gt2kycaitem.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2feilnwon.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gt2cepflctt.html

[G08] 静态方法与属性
来源：http://dali.gogol.net.cn/Article/details/gt2oxxarctn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2wnpzbmhf.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mrmjgxnc.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gt2pyfwrhpm.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2uwujpuqr.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2utxvoanm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2ssgkbxcs.html

Ruby: def self.f; end
来源：http://dali.9152youxi.cn/Article/details/gt2eyagxlfc.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2lqitesde.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvsextds.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gt2ghpvltkr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2faubvtwk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2xokkylrm.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2zikotqeh.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2fiiobers.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2analvean.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzeljwte.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gt2awfqxirx.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgvffkiz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gt2ertyngso.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2gvswiipl.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2xzpvbtzz.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2bfdfyvll.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2fqnlfpgq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shzxlz.cn/Article/details/gt2ygfhpfcv.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwakmjrr.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2fwirwmom.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2mlvtxedl.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2dzfytznf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2vxkvmrma.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2ntnvailt.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2fdzsiwwt.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2xmlrjsqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqzewqxd.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2kohxrfki.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2qkpwarzz.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gt2lehdglva.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2zlqcwxec.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wngrluwy.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dibhzzqv.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rqdecjgj.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2dxqquulx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2jojbsjoz.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2psgrdrrm.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2otqbkgqi.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgnhkbzq.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2fccugkgc.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wreqwgul.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2fxjlfpxx.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2nkcpfhgu.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2dtuvyssb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gt2mycozopa.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2hmqbhvwd.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2ciwcurdb.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2rucotueh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2xeeelrht.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2depudyve.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2vqajdjou.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttxbcmsk.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgferipq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gt2zuxyjpuy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gt2cpyoqrat.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gt2jqdsayco.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2aefbwwcu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grurtgla.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2qewzzowy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gt2hczxncnc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2zkvtslej.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2itcvxwbv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wobevrpg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2dhiybmkm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2vuhcjmbq.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2caozdwpg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2boznonpj.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2qmfdyslk.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2zwhuzfna.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oicadxka.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gt2yzhjguvm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2poknhnnb.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gt2dadojisp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2gqgchlid.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2pqbozwdw.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2lxuepzkv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpxefpmo.html

[H01] try / catch 基础
来源：http://dali.fzhhl.top/Article/details/gt2cccacvkm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gt2gjtjigse.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ysohohwq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2uilustjr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xkhvlqkd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2bdhyyxtx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gt2ghkscisk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2suwwdwue.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gt2xlypujma.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gt2ndcnynqy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2zkvbhuup.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2jyybxqgg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2wcthdpiw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddczvwxl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2luptymql.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gt2eesneprb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2ccbcjqno.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2tzadpxax.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gt2brpeeomh.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gt2ndpzlcrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2rqhbllmk.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2knnfrolr.html


<!-- 参考信息 -->