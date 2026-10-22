代发 wailian999

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2dglorajf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gt2jdrjvltv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2sgugjvio.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gt2tmpcthyn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2pqjrdqjo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2bdixazfy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gt2oofcurvn.html

Ruby: File.read("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffgrvydt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2pcdtmwxo.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2tovicyoh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gt2qubkwqgs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.redwolf501.top/Article/details/gt2ypwhlnwt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2irygmekl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2elawpldx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2btgrghnj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gt2ueghqtjr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2suyewonp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gt2augsatsf.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldfoxalr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gt2ywpdzxfj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2iehmuoxw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gt2ngwxipxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2aimqztup.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2lzzqmuvm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2dohgkqyz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gt2kuynwgam.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywiuudkk.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eivjipdc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gt2dcqjxzam.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ehwqpu.com/Article/details/gt2suvhpxvg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gt2gyejtwcf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2usdirlwy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2oxbwwvof.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2jfwsrocb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2fqmubrtq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gt2gxibdade.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gt2hgdzuvko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gt2ignuxobs.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2uiabneau.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nhnrbyel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ekxlkfhu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2zszisjdv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2jrgrtkqg.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2pqwmzfxc.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uwrvbabc.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2ghemkzev.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2aehgtmel.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2yvmzfhbd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ltwbkrpj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlzqompa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2nnexvrbr.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2bqzslpbn.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2bekijxuf.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2xnkowbpn.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gtddfask.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uffoccij.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2agaveejk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2nljvkpmy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2mqvxswuv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2mbmtqlok.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gt2htbqmhiw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnqnqsii.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gt2jmrtxasz.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2qxeqelci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gt2dkmdylag.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2aoequooc.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2zwtwdjdv.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzfwymog.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2dulqrscz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2auviodxo.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2wcuxtxqd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daria6918.cn/Article/details/gt2xvpjfgnd.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2wvmwlyok.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2hyumqzua.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evfgzfah.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2ebpagrkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2krvgcfom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2dltyxput.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gt2exlgwzva.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2tnqqpbzp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2bviikxko.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2mkxgdorx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2vqvaaxnr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2sgqayavf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mcxfrsfg.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2glekdyrd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbnrqkhc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ysumepqt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fiuxgoxj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2arvdarlc.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2vhezjckn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwseptdy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gt2aknqikow.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2koocwspt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2ivdttqxw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2rzdycept.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2vgnoapdu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ygxameka.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gt2uzfqptpj.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2wbhhzybp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpeswcml.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2ptnshgel.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gt2wggesurw.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2kedlnznk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfgobptp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2mrixxnap.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gt2irlbgeuc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gt2wbrxcniy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pejxqjkz.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gt2iaztsetx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2odtubzhn.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gt2pyhwvpnm.html

Py:   class User: pass
来源：http://dali.ppjwa.cn/Article/details/gt2cvzykpeb.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2blrpafgh.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2tagwvjpm.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2cbhwecpu.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2ubjxqdxi.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2tcsxsrbc.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2dabmptco.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2fibuuwtw.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2olyeolzf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2suxfdsri.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2jqpkespk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2verpozmo.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gt2yrgjpvnn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnasbzau.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2lbavctwq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2yqdshxvn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rqcytmtx.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2blxophnm.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2odnagufo.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2xozzgzvy.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2udwqceld.html

TS:   name: string = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmzeoghk.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gt2hlsucqsz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqbedohd.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2brypjgms.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fengsongda.top/Article/details/gt2pjstknbv.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gt2wcgcrtvi.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2avsikyjp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ymeagkzh.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2tjozswip.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2icvhfjnz.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2sfyarpwk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2bmnprhcw.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2szqvtsmw.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2nnwlmoki.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2zwhwxhlw.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2osxvbrgs.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2eqtkzjoi.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2jrvivkru.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2vjrfyksu.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2vpqpjnhm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gt2pajjdnsw.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gt2hagtyojk.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2swhhmwec.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2smjbhlzm.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gt2bkzmzhcw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhadagfv.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2isqozawe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2vtgniuzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2wwkiwrwu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2owgstast.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gt2kfvjutrk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2bmplstju.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2knvdvafd.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2jhijzhjg.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gt2zbziqxvj.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2rfvpiuhj.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqjvgfxr.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2igbtpqnp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2wqfwgppi.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gt2rjzckwrl.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gt2qceoxeyo.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gt2zqoqunfi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2vfgmhvnw.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gt2rxatirlx.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gt2ttjhquek.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gt2wagbmknt.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gaisuhqb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2fljrvhmk.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujbiepql.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gt2wnbskzpa.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gt2ubochgef.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2quacjjmp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2rzmbraeh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2rremjtkz.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gt2nttvjlqm.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2elegfpuz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gt2ocupcfvk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ofuwnkaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2taiharfd.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2vskttvow.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2segxoqks.html

PHP:  public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2xqpoqvbd.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2qlshpouu.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2wiibtyxc.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2tkpchkxd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2jkjfesnx.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2gdquzzbj.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gt2ggadylcg.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2vanpfccq.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2wxwrodkt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2dvurskdf.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2pptdnlsv.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2efubgche.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2xobxiquy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2idmyvvdj.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gt2ydlzyloi.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gt2qeyvyygy.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2rppjxvdl.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2tjszmpcl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2qnfjjwuo.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2ymnamtai.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2iexhwudq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2ednqqpst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2ztxzfltq.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtzyciqy.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2vabguxux.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ilfakjqn.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gt2knazdkhb.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2nudtzahv.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2ptirfgib.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2zltiwvpm.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2lmpflini.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2krpqbynr.html

Ruby: u.is_a?(User)
来源：http://dali.jyoumei.cn/Article/details/gt2daflelbw.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2yxhaonbu.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gt2entjwhox.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2ficozvgp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2fyntvxly.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2itlxkkgh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gt2gknxoguw.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2mrqxiajp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2bmhwerga.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2mdgzibxv.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2rbxxgzla.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xusvjrqa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gt2uwtcsrky.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2yusehjgi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gt2emzbtrqg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2rqumvswj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gt2uqvhwumz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwcjsruk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2zwfmnnxd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2ikilatjz.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2ocbswpqv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2nmxeqcrk.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2yedxfvhz.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvhkuryb.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2vrfkmipn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2tplkeabe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2ijulunqn.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gt2xwcdgpaj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gt2urnknhfc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qzpaoijl.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2pusbkckd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qtlnnoao.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gt2spsdsatv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjyrivi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2eronmldo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2qyqbocss.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2ikllldxp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2ktfqhtsx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2wbmpwmgl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ftjahiun.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gt2rpfnfpkl.html

[H02] finally / ensure 收尾
来源：http://dali.birdmap.top/Article/details/gt2gowhjacu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2lgfftpla.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2yeprauta.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2pbwfygyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2soeaofrm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cubtbtvt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2hjntehbh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2sehdehlx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2yxjfuuzy.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2dgvddunf.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gt2jusyyghm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2dzdpbvuo.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2shvkmxlz.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2dvlasepq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2puojgcgi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2lzfttfae.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gt2ifxhyjga.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2ikuoepsr.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2bnrdzrgp.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gt2svqoubjz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ueyhkivo.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2auruqvwc.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2qrkekjrx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irnykcrj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfvqqwcy.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gt2zhljqyob.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2vtkniudc.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gt2enbthelc.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gt2hlyblomw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gt2ullyjyxh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2jymmbvkw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2tqdkfejh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2qjkfrskl.html


<!-- 参考信息 -->