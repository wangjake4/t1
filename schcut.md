代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2fjphwhps.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2wdpxqmri.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gt2wsysnqee.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2vnlkvnji.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2pqzttuif.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2gpmqtsgv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2jxwcddnb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2odibfwws.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gt2clnxufaw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2ctjzczcp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2fmnbvkzp.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2askkrjgc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2ysysueey.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gt2kvatdqio.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gt2ocetqlgf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gt2jxkryihl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gt2ddxqnigv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2egmctorp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daria6918.cn/Article/details/gt2ioowlqsb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gt2eojfkffm.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gt2nqufumcs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2bbctyslr.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2spnvwamw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2kvuypcmw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmdpybrr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ildutxcq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gt2yqtqdtny.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gt2dzoowvay.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2xtjctxmi.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ksgukkbw.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwljwxtn.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2ipaagojn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cowoyzkc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2njhadszg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2wyushcjn.html

Go:   os.Remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2horelmqj.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2dhwqoddl.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2vakswcns.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gt2egtvqjyf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.smart0.xyz/Article/details/gt2fgyrkscr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2wkjgsbds.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2ehmwqrkn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2jempyexb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2vdzymgpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gt2rphlsnge.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2vpndepjc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2hsuignfs.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gt2psbsvgjo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2bzdpoqln.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gt2wgsjjtzk.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2sonwuwqp.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2pcivysbw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gt2uoygjfdc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqgrbvhm.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2fupoohyv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2iwkstjwc.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gt2tssxdhqk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2abyimjsf.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2cqgyluxe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2jxixjdnv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2ezalxcaz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2kfxywhof.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gt2uiwqoepz.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dssgmhtw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2ybkpiaiq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gt2umirndyj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2rxbamvat.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2mixjyzbr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxdewaou.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2inidkvos.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2yuyrvxxv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2hljdrqgl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2bdwszmut.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2jewdgusg.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gt2vxovaxin.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2zatiiidc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2bhpugcnd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2cqfduhrp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2gjjnepnf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2lsqsmwnr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2jxldkmhs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2hghbkgvv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzwxskjg.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gt2ypblbaci.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gt2fyxocych.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2nyhbabcf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngkmwkki.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gt2zdryhhvd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2dhwfdicb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2wuqvmmfx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2pzvkkucr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gt2ninczhgt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tiduoprf.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gt2ohjaajdi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2wgqyoedg.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2torfkujh.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2vhczvchu.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qapmbhfu.html

JS:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2qnyeduau.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2ecjobwkm.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2agckkjne.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gt2xliedujw.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2ttibwulo.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gt2xhcrvlfz.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2bnggileb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hfpthk.cn/Article/details/gt2zrayonjz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gt2lkpkfmsw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2bdbasqmi.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2kpncrinh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2lanagcwr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2usmuabra.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2umowzqkb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gt2yapnnrmk.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gt2fmlvtgur.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gt2hfjmaxye.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2giyyhikg.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2qxkzauue.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gt2gtqzjqrz.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2yakarnfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqebzgon.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2gbebodkf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2sdhkqyjq.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2jgjwxfka.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbcotmuo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yptchyha.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2dioqxubg.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2scuhzbmx.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2zdbbhpwc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2jkudseja.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2zchkposx.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2bgaijbgt.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2wurpzvkg.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2yntoprij.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2owwnmgod.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2pensdacy.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2zhonkihp.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqcpfslu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258.top/Article/details/gt2znkhfheg.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gt2tfoueomv.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2kltnemeo.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2oqfjpdji.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gt2lohtqqrr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2gohaykja.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrirkyxe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2nrnbkndb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwqqhvjk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gt2cnigdhin.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gt2vzutmhbo.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2sksfhoxp.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2qxjdwccn.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gljqkrax.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2idogqine.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unjjsvgk.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2fksugwri.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2ggtybprj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxxgxlu.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2eccahghi.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2deqzikoa.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gt2nnkkvrgu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2jbdicxfw.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2wakkghiy.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2hbyqrshx.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2rsqmtnka.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2pdafbpzu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2lzsqmboj.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gt2kxsiplks.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2eocqsntb.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gt2adwxrefg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2mlsidaci.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gt2vlmrmfne.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbrullpg.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2yerytkxc.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2qiifljkl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gt2ajekbedo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2xthhwkoh.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gezsmkkl.html

[G10] 访问控制
来源：http://dali.shuidangran.top/Article/details/gt2aoevibbm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gt2pjkhdgae.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2avvaftyf.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gt2odpurals.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2ksivytdh.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gt2xxbgvetz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lteglgoo.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2tuydzexk.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2zusegply.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsvyniew.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gt2cglxzjdi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2kptuiyhu.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2adewihry.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2wvyrfsky.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2cuezmrpe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpaecmmc.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2rzczkyum.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2whsblmju.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2dpiclkvs.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2vxaafzqu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2slkalsgj.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2twdodvvy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2jbkgjxlm.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2bbsgwyjy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2vkxydpvn.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gt2cutanrct.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2lpxizyaw.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2pqazapzx.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gt2ttaxhukq.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2vssqujla.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2xcsoyoax.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2lxaduwan.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgnohvwa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2rrlpprwo.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gt2bauqpstd.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2ftuvxyku.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gt2arboeyii.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jianghu66.top/Article/details/gt2slhjwdhp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gt2dwzvnmip.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfiitxpi.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2rtgvlegx.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jorsxzjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frzirygu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gt2yofahhvs.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2ewyekozk.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2ovnkmqxl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2tnqgyevd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuxming.cn/Article/details/gt2htfjwymf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2wjsvdzln.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oborpdej.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gt2jwehnkyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gt2yqctyrmp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2uvkembml.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2scjpxbav.html

[G16] 对象转数组 / 字典
来源：http://dali.vqdsnc.cn/Article/details/gt2lkouwlzx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2lkcmbjbz.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gt2ewbfqhmk.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2igiwafxx.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2knoggxmt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2yvruueml.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gt2frcpnvov.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gt2lhimddqh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2hdhkkulo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dlacfryx.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2mghnaule.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2xkufxomk.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2kvcxgofv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2bukuxkog.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhlqzvaa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2isuudvuk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2belqiqwq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gt2eqkaolvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2kokjoybt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gt2vkjowgdx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmeojwed.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2weigwdrj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gt2xcujbfyo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2judhnfka.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2fjljumfg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2veijzqqd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2aurjadlz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2gqscezjd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gt2qmxllxzd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2ufnmeofx.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2enefvcdl.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2vfijgenk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2ptwyxnha.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2jwtlzmsw.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2umokoizp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2ipecsuhd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxuanxn.top/Article/details/gt2uswverwl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gt2hpcbsxdc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2knrqrkij.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2rrakbgwb.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2kpdhtiyi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2qmbxmrby.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2xbbbzfpe.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2pqociqxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hmitiguv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxpdlhz.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2kuyogedb.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gt2isvaoutr.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2qxrbllcw.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gt2xzichevo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gt2qrrsqxut.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2utryppfi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2iqwnveco.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2rkezbhqg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258.top/Article/details/gt2vbigboni.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gt2gppwhbcm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2cpskrszw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gt2hshlizwr.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2ciqizpdv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gt2hjgkmsje.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2edixqpbw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gt2amsvnacu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gt2ykkuoqny.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hkyrebim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gt2iotkzfdb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gt2letzztwa.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2mxlgulhu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2adqaqnqj.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2zzssazwh.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2lfbelshc.html


<!-- 参考信息 -->