代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtepnowdkr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqbkndtng.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gttkqsmdxg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgokopcxl.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmjtnqsod.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gtkikibylh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtyhssyuls.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtysxlkxwx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtcublpwvc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtsegoaucd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gteylpeqei.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqcbslete.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtwqhrhcof.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtdusiaydk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtsqaidtio.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcsyqpzue.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtgiutclig.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtgzdpeauh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctvnmkan.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gtuqhzypgv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtmmrqmhqu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtzgpktguh.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtwyvvnhku.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gtrwekfdqb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtvimvohku.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtwobgyfke.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtaujcmkas.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtjrciwucb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtvfdyfgbh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtvbxlshgg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtxujqzozn.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gtorfbsxck.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtanjqxewk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hnxiangtu.top/Article/details/gtcjarofnu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtsvqdqarf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtbqhfddvk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtgwbvlnak.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtdfzfaszn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtbljgmimh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtqhbbofpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmolqcfdk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtzdbeaatz.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtuuescres.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtalebukav.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtquzavdqd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtgkeybtpp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gthbfgtxez.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtlyzhyxhy.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtodiqotsj.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gtgrpscgwi.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtcxwuniqz.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtidmffdeo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtyntzvtvi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtghqcqxbp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtidljfjjr.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuwpjhrhj.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlfbfbonm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtpjlaroti.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtooxkmlye.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtrelvecqz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthywvqbfw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtofofdqpn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gttjdsbcem.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtowrfauyp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtubcbhfhw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtbtjqdgfp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gtiojlsyax.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtcxgxqjqi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtqoytrsrs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtsmlypuye.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtlcotxznm.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtrigtypco.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtnartjntg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtvuwiyefo.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtpnuknldh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtybnapeuy.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gtamnbmbiv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjhphfoqd.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtmyxwqjjz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gtwhtvrdav.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtzcaiapcz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtbzuxgxla.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtgkbkchpd.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnzxinyur.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtployhwar.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtcjccbasc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuypidqlu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtoiokyztw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtewhqzwda.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtuyfdkvcx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtfvventdn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtsxtqiljh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvlvdlqia.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtwxkizmzs.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtaihkcntn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtjczojgpf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtasjvehei.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gthpkcquji.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfwxzofgl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtqnureitk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gteolshfds.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtxtqyoyey.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthntelfxj.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoipkyps.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtqkttvtpi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtkuqtobxi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gtcxfccpqz.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtstrkxaik.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtvasovwjc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtckpuvyva.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtvzctwrhk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtkqjnrgbv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxkcwzifc.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gteiwwkvgt.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtimbnlmcz.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtkftwcjsn.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtdqxdjrjq.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtfdcobejv.html

JS:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtlpxpjgsh.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gtsauddhtk.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtfuzdiewg.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtvwdrcpjy.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtdigyssaz.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtlzlszset.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtkeykxxny.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigfzy.top/Article/details/gtmmkfbhmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtfgbojjtj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtxjhelkyt.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgiuqcymw.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gttxgazxzf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtuyzcxxvh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gtmcnkunrh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwwseykt.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtgoilites.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtntwxukti.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtcxviqups.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpnnauok.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gttuxtbmri.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gthfttvugw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gtennqopkm.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtbhsfbkcu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtxktqvfpl.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtlsmxxqtd.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtdenfqmnn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtarexhneh.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtlghioncz.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtzfqktymr.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gthoipdqsr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtgxvwlrib.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtddvsvoyw.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtpmjlzckl.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gtpvczihgp.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtykieuuam.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtjitsddxv.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtmvgmzvev.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtwqrxmuci.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtifezdoya.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtswjmskes.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gtdihmewzi.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtcvbcdhpr.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gtjbfazwyj.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtbeqmgnas.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtrrznxcno.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtuitqjliu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtosvpnhoh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtxbcnqqbc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtwxykvawq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtpfycscow.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtbsvqksic.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtzzsecysw.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gteaxmxdqy.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtgvsuwnxs.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtmsfowzga.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gttynzqzgc.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtkefdjvos.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtixomdinl.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxwhobrh.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gtbsranpcu.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtsnhyqqif.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gtvgmfpeaa.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtatfgypuj.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtzgchlazv.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtycvvtbap.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtolkqmanx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtoccfvrjt.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtqymgtyvz.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtqphzkkad.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtcyxqtqyp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdabvflm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gttibhkbwc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gtnuknqxcr.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtzjmrpybr.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gtvgstxujl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtngqmbhtx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmviwelmx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gtieosbljb.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtvbnaobly.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtioxilzjq.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtaetmzulp.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtshjrikhd.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtebleqpcq.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtlbmzlphy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtikifexdr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtlztvkgyj.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtixuzwohd.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtfrofvywt.html

Py:   @property 与 @x.setter
来源：http://dali.yanxiufei.cn/Article/details/gtebamhgir.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtrwmqzmbf.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtiyyqwgst.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtvehpoptk.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtmsxvhyqz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtbuzvzhrp.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtrvabmtna.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtwdamnpga.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gttecrtaxm.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtarcwjvhe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtimxnqohw.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtrdrpeglv.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtcbwzgqby.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtbhnitgnw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtejeqykbi.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtnrpblnxi.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtlswkdioh.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtprvvbymz.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtgimirrii.html

PHP:  $u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtrfpgmfay.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtbzixckve.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnooyngkt.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtiqsirceo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gthqzfnfgo.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtfudaalpm.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gthssdycnt.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvvgxlvn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtnywvfyem.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtrsxpigsc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gtjnvlnbjd.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtyinobtyg.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtqneljuqx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtumrhlnib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hammf.cn/Article/details/gtiljujauq.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtuapizwxd.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtsrqisgnn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtkcsvjadh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtajsjvxaf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtxuvzcary.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtoyyzotrv.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gthkmmvdle.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gogol.net.cn/Article/details/gtjqibdhru.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtwjhudrmc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtzobozwjr.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gthzxmyhqs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtyfizzgss.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtxopoxpmt.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtytnxkieh.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtkwswohrl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gtfftjbvwl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtwzedqcmk.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtvkqqakml.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtvmndodrj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyflechdo.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtbdxixewg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfqabygjq.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtvdgfsdug.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtjlwlzhum.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gthgzzngyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtehasddqw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtycrvlgze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtzpbkdlxu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.havefunace.top/Article/details/gttwleafet.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gtbdqvzrmn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtbskqwzam.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gttpevlefw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gtphmkkscs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtrvtxbtuk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtijceickm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gttdqwgrcl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtknhynglc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtftftqwzx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtzryyhwab.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtbnvnbfnc.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtechyejlo.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxthojtji.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtjchtghnf.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtampvxsed.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtfhtunaki.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtczyazoxd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleyvvghl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtsvhevozz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtyjfxhsbv.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtlfggukbk.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmahfuxgc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtaxuuulav.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtrtiskkuu.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gtufvemlya.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtedirwhhg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtmtgshnue.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnrmumyjf.html

C#:   class MyException : Exception {}
来源：http://dali.316326.xyz/Article/details/gtpzkdyokt.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtecginybz.html

Py:   except ValueError as e:
来源：http://dali.jinqigfzy.top/Article/details/gtckuzhbeq.html


<!-- 参考信息 -->