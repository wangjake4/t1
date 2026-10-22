代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2dqzsbbbt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gt2lerecqwk.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gt2xdgdkpqe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2yxzcbvzc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gt2iuenjncs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2xadsqbim.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2niodcixb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gt2soptmale.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2dqxqdalb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oymxorfb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2gychatxb.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gt2pbrukjnb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gt2xifnpmxo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gflqfyga.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2vujzpbir.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gt2ssmzaoax.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mvjbbxwv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yongpay.top/Article/details/gt2ergluhxa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykekpjlv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gt2fpqtcuch.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2aepxrarx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skksxyur.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2spbuvvjs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2fzgxoihk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2qhtusosu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2tdizcptv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xziqi.cn/Article/details/gt2ajweohsf.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2vtaftgzz.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2amlihmoq.html

[F06] 删除文件
来源：http://dali.bjfxy.top/Article/details/gt2qutueqse.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2myinbtje.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2grvakvil.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ljhegypy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2nrofvzhg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2kgvajerd.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xuiefpxu.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iblilyad.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2quzliatv.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2dawdxbxn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2okpxuvwl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtkybwwo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2acdxwkdq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2pydnisle.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygmmmpim.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gt2ppuixrbm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pytlydvw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gt2hhshigot.html

[F08] 遍历目录
来源：http://dali.hnqzz.top/Article/details/gt2njkkeiyu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2yupwwtxi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gt2jnexsedk.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2qemnkuic.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2vxjtaxaa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2lzsuczga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2mqqjjgoi.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2jjuqbzsq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2qxydnpgx.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2fvcyamzn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2hrglmjcl.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2giodgzoz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2voydiyzk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2yqargfhs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2vybyslnk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrmpjdag.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qclkareh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2miygwfan.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gt2uqbibshx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2zorswnxo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2gtfhqzcv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2hyhbwxzn.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2kfsmvmzy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2bmpmivej.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2laokbnyk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2yfzmjaoo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2idscpkhy.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gt2ctgqljhg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2knzdedhu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uavsqfec.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2outyagrv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqfxfxvt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gt2svycyajn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gt2cnaxfqsa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2jeivefzz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2drggqyrx.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gt2znsqfkjs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqsyrurn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2jwtqngvw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2tlsmjohg.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2speyaxuy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2savqxddb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2bwznotnz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2ojxqexny.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eglqasmz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2eaarwecy.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2igrhtnrz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fritkkcx.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgldaunm.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2tugatjme.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pzfdduaq.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2nalgjaku.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2wlqzqzvx.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2uvwogalw.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gt2fkikmerj.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gt2kayvslkz.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2bzheqsyx.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gt2vojaltzs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmpwiqpv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkejrftt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqahdenp.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2hawgjlmg.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2caqweniz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gt2gkzpooca.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gt2jmzkzieq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gt2rriyehra.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gt2apelilin.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gt2qzzafbpg.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2hljwiwgy.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2fhgsmfhk.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gt2qldphvut.html

Java: private String name;
来源：http://dali.316326.xyz/Article/details/gt2fsuaoout.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2cihkrcdd.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2aiwmxhcc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2ahscujni.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aawrgwgo.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2aihplori.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2movnoclp.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2jmfxvkrb.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wknnpuhk.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfpmlynr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2kjqoubia.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gt2mzqwnfbr.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2gqrrbrbp.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gt2mermwawz.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2zwryghrz.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2cffqcrng.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2spvmjwji.html

TS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2pqkjjske.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2hqpkhbfs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2bndxenvb.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2btqwbluj.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2wduqdphy.html

[G06] 重写方法
来源：http://dali.zhongyouzk.top/Article/details/gt2dneaohff.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uaguhmhq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ldrglpcc.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2ptckdbzo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2lnabpmgp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2eorisfwf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2kuxcibnx.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2vnfzgfrg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmtcsagi.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gt2cichjcwc.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gt2biqcprhi.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2efttpvts.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2sasaoxky.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2dzppakuf.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2hkncflxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2piiwhxjn.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gt2fyxzjpce.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2kexpxdhz.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2urlzilwm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2hllvdldn.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2txgqvnuy.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gt2htuobkwc.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gt2jjjaljwg.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2diaxekwj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2hjiweduf.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2yrzpgwlk.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2hydeaxac.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpxcejyq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2ysuazpxa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2guagdunk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2hnwdbotx.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2jlxyocpw.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2rznyrhjw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2kvistbvi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlajovi.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2kylznqnz.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gt2xpzpiigw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gt2xxpzhtsn.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2vtcfbdeo.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2frliuoef.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2yutrsjsf.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gt2zdniwbks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gt2vilesbrr.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2uanqeigj.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2vgvshstx.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2kkdacjup.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2laldvczx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dmalhdcd.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2obamdbjd.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2lcpwdasf.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2qnjfxpey.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2vktacmvi.html

Ruby: attr_accessor :name
来源：http://dali.316326.xyz/Article/details/gt2gebasdny.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2uwazrwcd.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2probefjn.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2wbtxefka.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2krryobbh.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2zqiqyzdv.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2vmadnore.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2jipkgpwn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2iaoxxvar.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2dsjcwphk.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mheyfihu.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gt2nzohkviv.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2fghsoasv.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlyftjer.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2tljgyafg.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2uhhoczcj.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2ixlhiwdf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifsjxubj.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gt2gjxerkbz.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gt2ltjmtgvc.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gt2kffbftoa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gt2stqsdczq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gt2pfwoemxr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfaeuukv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhongyouzk.top/Article/details/gt2zqtjyhxz.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2agyjnuml.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gt2ikcenmtm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2waflpytk.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2qqjhylvz.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gt2lemdbnwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2czhfxzkg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2sttwkhrc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbhzkaus.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uengkicu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gt2erbtkutx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gt2ahwdwbjd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gt2tulgkupu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2gaqerwfo.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gt2zfqsgumg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gt2ynjalyqd.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2dpfowhah.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lqjmnkdw.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ixjeyxns.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2mwuisyjm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gt2vojgupqf.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gt2yldsrdji.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2rsirzrby.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2nhlagrdd.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gt2gizdifwu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxolqoln.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2ooybgfnt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gt2ptmnohva.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2inicgmxi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2hdvwwjoq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2ffrocirj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2dvgzjchd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2ipnfhgiw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpwjbjef.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2vyjoaads.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2xvzrcfqs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gt2fsnnybxk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2jptdmyue.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2rkiyfofi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2fwnogqfp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2uezhaiwc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilbbyeyu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gt2illxgdva.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2mgmwoohs.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezwpzbuk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2jacslyes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2uhtfhmvz.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2hfzrwjbf.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjtueleb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2zhidjwui.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gt2vwppslpv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gt2kuspmipi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovhaxzjx.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gt2vzbimuxh.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gt2gygesiol.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2hpiwggne.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpdxufnu.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2dtnkwoqt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2peabmann.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2wcibiwxx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hammf.cn/Article/details/gt2bijtexug.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gt2ofemxwih.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2aufhdvdn.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gt2ptrjagnv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gt2vrquermz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2ilmxtchs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2qqbarcmq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gt2jigpbvrw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2uqogamgz.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2sxwwoell.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhwvcwyu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guowangkeji.top/Article/details/gt2alzaypdy.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2neqwdswi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2amdjanou.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2auwkopto.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2ybeyuwuu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gt2ejpkznyi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gt2pdhuwtjw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcwvgzdh.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2hxgeacje.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2xcmkhnab.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gt2mqpgyumc.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2ndgmekpf.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2jpcbtsgn.html


<!-- 参考信息 -->