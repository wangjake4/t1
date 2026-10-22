代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gt2wjrihtro.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2eaaoamgb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2bfaffgvu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2ivveavze.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2ceqfirvk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmvefunm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2hxzpielr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2nsryzxik.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gt2fdnydesk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.mhx1999.top/Article/details/gt2tyxcuvax.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luikcdgy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2gkepfeim.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2fyebzowc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2wcbrtfeb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jascmbsp.html

Ruby: s.bytesize;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2asddtnpq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2icxewbaa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2qujnovmz.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gt2rsqvynfc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2zevmmcgr.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2abdmmvus.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqgnnvhq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2zcuyxnqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2gighjien.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpywdcxl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2crfvmtbo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gt2nrdjepnc.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vimwrfsz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2ansupkar.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gt2rgammiyc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gt2fnlbkins.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2glokebzp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhdfoxon.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pozmvqyp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2olnoifwp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gt2xhdnkkaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gt2cygcntna.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqnzgojl.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvlkmqwc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gt2velcaftv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdkqurff.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2qxgcdnnf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gt2xhjfilfy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cvkhfmfb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxilqmiq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2skqitgnp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2ufgvhjmg.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2nejjcxtn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wklyzxrj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gt2jmvpyqqj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2gelrvtii.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2lcksztsd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwsajeyh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2lsozkmeq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gt2tfdfcnhj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2napkfmni.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gt2lnpflozy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2fwyegvsx.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqvqgxms.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2vhhvejkm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2mcllmlez.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2junnatve.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fzhhl.top/Article/details/gt2rbxxbuvb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2gziahllg.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2npsoyugp.html

[F06] 删除文件
来源：http://dali.zdqjudy.top/Article/details/gt2wykqhlhg.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2lvbccwbf.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2bktkpack.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2hnclteos.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2wefnfudq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2djxaponr.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2lalrxjaj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nponstxw.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2gkhmrucb.html

[F07] 创建目录（含多级）
来源：http://dali.fengsongda.top/Article/details/gt2qjacjdyy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2reemrtrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gt2dqyedmvw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2dknmgrjx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2xchhkmmq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2nosfdhii.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gt2onyknlbt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2ycvhhujs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nwbrower.top/Article/details/gt2olrbyxlp.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2vfgmzviy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2danwbmxr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2kuznrqrq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2jgtyfgfa.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2vtcytdny.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2jpdhrnik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2mnibpqnn.html

Ruby: Dir.children("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2xaehttqj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2xttwsylq.html

[F09] 获取文件大小
来源：http://dali.meibo888.top/Article/details/gt2hetxkvxc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwehsba.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2uslhaiqh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2qramqfdu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gt2wldmpjay.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2kosrnsdb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2ofnwivqq.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wijqydcb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2jsxbsxfz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gt2epjsiyvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2klcyxhkl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2vzvbtdci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2gvasajzb.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wbftmivl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2hbedydjj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlvygbtc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbljiarz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fjuevlhq.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gt2zncijhed.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ngujjfnx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2zejyprmd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2atdkbwjk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfirkdoa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gt2ntnnxgap.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2ignwkhrg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ydnukjwx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2fgnmnfis.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2oqelqmse.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2nziwyyxm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2obkdppgn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gt2gmjzekmm.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gt2hiuvkpwj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2rfwisubb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gt2orghdpds.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2hkgkqxni.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqdtqqk.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tezollhr.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2amhstbfr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2qfveaxjz.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2wseiqgrd.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2couhjzvy.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2zwmlwzyu.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2sniqiplr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gt2vaosnkho.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gt2esgebfsg.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gt2yhnhtfeh.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbzhglfo.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcoxcxyk.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2fwibsihz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2hrudetbr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2mwmzxorv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2kqvtygte.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2tpgnhjhy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2oqynswbh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2hdbrrywa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2niipbqsg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2vbzqtasv.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gt2xaurfizt.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2duvpzeou.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gt2zynpwjoa.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2ldcxfejs.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gt2pqzicdlf.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gt2qaztfgrz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gt2zcfjwqya.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tduqgypq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2gwfljciw.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gt2qvmwrncb.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2oovbkapy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2kikxkvjj.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2aoyziwjo.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrphiqsi.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2znirjtye.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2ogcxoxny.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2wrwcopxn.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzzlauqp.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2acibswxn.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2onyohhkg.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2kysewgnt.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2zembpoug.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2oadxvoav.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2kvlyrjkk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwayktcv.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2bhtdpexa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgvygrr.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2tcuqvxxf.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gt2vtliupdd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2egitzftm.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2rjxbiett.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2pwaahgid.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2torszhqj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gt2onfcyhbx.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2htuhrhbb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gt2ysohtqjf.html

[G07] 调用父类方法
来源：http://dali.jinqigufen.top/Article/details/gt2hqwtiliw.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gt2zhpqxlto.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gt2lkwinqxl.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2krnkpxfc.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2lajywytq.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjbkhrex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gt2celcmtue.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2zdjkzpww.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvspzqxa.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2yzxwttwz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gt2lqciuxyd.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2jzucenlb.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2pzhsrrfm.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2vgmjzmax.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2ncilssde.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gt2cydedncj.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2jksldgam.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yioobmzo.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gt2zruqgqww.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2bjydmhsz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gt2nhiulxdw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpzuocmq.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gt2bwujblsp.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gt2slaylkot.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2upugcgpe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gt2elsbymud.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2pwxobfab.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2bzzlphjt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxxatqdz.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2sdozjooq.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gt2odmasavc.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2pzgxyatj.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2boraffcu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gt2mzuaxxyc.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2ozmxwokk.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2awwoipan.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2rppoilqy.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2lxzjgmtd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2meglzctj.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2hhzpuqca.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aiiltmfp.html

Java: public String getName() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2erqcmicp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2qkljiqdf.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gt2wbecgpgw.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2abemcpdp.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2obbuodnc.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2vmqsqwvd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2irqutxyu.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2rccjqmzp.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2pqgkdeaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2qcmhsnkx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2dyslfjxe.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2ttuwkkyb.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2ixpjjchf.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ejgeiqse.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gt2xcnssmhl.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2lthvlbbe.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptuocyau.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2nuzslvbq.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2gwpjuggz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrqrzjrk.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gt2ybjkuwkw.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2tplqsidw.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2mpfcwlnc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2cybcjxcs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2eugeyiqp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gt2xavgsrfy.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2gylkzqls.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rdjeurpi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlksqrzn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2rzprzerh.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2nhrxrzhm.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipqbhltm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2lohblxap.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2okeymsly.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2lydsdlwb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gt2selqbtlg.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2unvvilpo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2nnlklzow.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gt2eubhjzac.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2vbearqlo.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2qrbfcxfh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2eugkorno.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2mohxfuve.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gt2bugzesij.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2klsjlroz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2wgctfanp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gt2onlavigy.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2tbxnpgwq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2kaqalqfd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2djucntkm.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gt2cnnxlrjz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fcjfbfqr.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2rnvczsfd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daria6918.cn/Article/details/gt2mxbmyhzs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2smqjlyjr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzphmtqu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gt2jcbfsomz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2pekvdzgx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2nkckyyms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2xtrekbhc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gt2blrikpco.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2fkkdjwwp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uywhwirb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2mnbtwjnc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nayanich.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2elqzyper.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mddvlyzi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gt2ujmiggjr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gt2umgvwvmh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pfnznqjv.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2iopcvovu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gt2hisvqpfv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2sgsryuhy.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2ndzeqtvq.html


<!-- 参考信息 -->