代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gt2cyqsopnj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gt2fttmirhy.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gt2znlyzfco.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gt2ctbuaeic.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2vloxbntu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2dpywxlex.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2wfhbtlqe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gt2gejunawc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2zpdyotkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2eoawoygn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gt2ltqxlagn.html

[F04] 追加写入文件
来源：http://dali.gogol.net.cn/Article/details/gt2yvhdmnrd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkekauvm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gt2jsyamfsi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2bmcybqpe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2ecswfcom.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gt2qdxrhowz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gt2kpfjpilt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2soukflhx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2doeiurzh.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2pdardxrs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2abfllhqe.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2iyxhchss.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2dhuneumc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2hedobehf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2eupxyzcl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gt2phjjslik.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2giossmmh.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vkwjkimm.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2safhkoyw.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2xnffyuog.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2sltgolhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ggpboqgk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2dgmrgymp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2ppusxsck.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2yybkfray.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ewctpvvl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2gmnuyscv.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gt2kpdzlumv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2aqusluxf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2gofvkxzp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2ktcjmnic.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2pkumalab.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2ywezerir.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2jkafdbwv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2dznatdxp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhbnpkb.html

[F08] 遍历目录
来源：http://dali.ybcxt.top/Article/details/gt2belglgfq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gt2agfceugn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2knsqfuxy.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2uwadvxzq.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rywfhczy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2whrxihua.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gt2rhleluyy.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2zyqwmuuf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2rywqutny.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2rskthjxd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2uathjoak.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrabzvep.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2mqeahktv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dncyrltv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2ggpqspgq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2vgoldbpe.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2zsjxzarj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2jkicxexs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gt2xbqzyhls.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2vukribij.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gt2xrhruwad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2xaxayuuv.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2mcuxuydh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gt2kwhjbxxr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2chaluooo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2doycippc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2uvvrflat.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2bhgattwx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2nexrllpk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2qbegpxkl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ttphzkeh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2vimrojfv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sftxoceu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gt2xiorxxsa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2ghurqiih.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2wayxttqa.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivnrbpnn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2zwinjnhn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2mvezjxsa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrryhrzx.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2okvumaid.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gt2qpvvsfhb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2coaplquf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gt2cnnmfbtj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2lcboranq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ootczeiz.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2obvcokjw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bnjzelhb.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gt2ktsvtqql.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2jgoaypsd.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqpwtxuo.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2mqpomwhd.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2eegmfesb.html

Java: class User {}
来源：http://dali.cucudq.cn/Article/details/gt2vpdnnekk.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2yjewvmkh.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gt2alycuikn.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2ljdljrfm.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2iidmmlfy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2zyrgxxpt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2zvmojqor.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2lkzbukch.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2kgczbutt.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2krmmlgku.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.9152youxi.cn/Article/details/gt2eukzfmxc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvwihrxi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2qlcvcbvt.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gt2iifafajc.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gt2vuvwukox.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2oorsfpsq.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gt2gkbrfbkk.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2mhvpgtgz.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2rjcvugod.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajvzzpim.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2bznjxpyv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2ymqrgrwc.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2tqnfehnw.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2mnntzzkh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vvryuykg.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoggaodc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2zdqwxnws.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ivchyghl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2erijbwqm.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvupvwfm.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2zczdadtm.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gt2yoyhphmb.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gt2eyraneyc.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2zyekgfpf.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqnnzlam.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uckkvfrk.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2kfyzljsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2jovwatfb.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gt2odtxygxu.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2gyqggxsd.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubwofbol.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2pxusajnk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2lzsikcem.html

JS:   greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2alkecvfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izbpyxyu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2hdbfavjc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2gfvjmtvr.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2limlviyw.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgaumoyf.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2bflngoap.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2mfwdvokf.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2zpuoduuv.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2ctvsvixa.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2qtjuahax.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2orvsobxj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gt2ntxkxiaf.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2wloncrjc.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gt2caamrbye.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbfyflpz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2wourazrq.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxbjctlr.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2apfhkdhe.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2ilpkaphn.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2npwciqgr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2hvnqpxpp.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2pdtkxtfr.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2lphotwcr.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubythtpi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gt2dzlwqqdr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hpydpcca.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2qixxuwwx.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gt2kjxlydet.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2adsjcfhs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2yowztowv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gt2ujkljaes.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2mvqpzyie.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2qtlvtkgh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gt2bgyjvguw.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2djvnqral.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gt2sxduxfch.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2fnnusnst.html

Java: public / protected / private / 默认包级
来源：http://dali.aizwys.cn/Article/details/gt2magnehjs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gt2grczipgr.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2ntninayl.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2axlzvlyy.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2tsmuvzlr.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nlpodboc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2pmxjojto.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ueioqvii.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2ambmhizp.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2kucncune.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2upzxhkex.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2telbyprc.html

C#:   public string Name { get; set; }
来源：http://dali.yangfankeji.com/Article/details/gt2rygkwgjp.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gt2nifjlrxr.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2nphrzltu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ijgvhbos.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2jjhbjzyl.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2tzxeqcgo.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fncflknv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2eddggawd.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2jlcsfegr.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkuagkqn.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2nxtuzasl.html

Py:   isinstance(u, User)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skyuomxl.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2hikrehdn.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2mduycrco.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2xvrqbxrk.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2jismjnug.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gt2dblrxlyr.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gt2roczoltb.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2umuiaqaj.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gt2lyibpong.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2bsexqlqc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vemteqts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgqdblyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gt2ukxdzduc.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zisinehq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gt2poqzlvqt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gt2xnfpfylt.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2feovgrlj.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2vukmrwvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2yzwovkuf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gt2lvgalvol.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eieouaer.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2zygsgzil.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2zknckjxu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2wcsysund.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2mxjodzvb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2gramommc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvdhzdcx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2hiupjzmq.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afwolwhr.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2cjobsarw.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2loifyzqj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2kgasporr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gt2huczqcjk.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2tjhcdnxa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2ikkhpnnf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcmxyawq.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2bhekayar.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dcktarel.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2hzozepnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenlongwang.top/Article/details/gt2vvzjbmde.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2lmdpmydq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gt2calceolb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2ymngopwr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gt2hqpviwfs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gt2nyrdmexr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuanzhike.top/Article/details/gt2affbvhfh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2elxtguxn.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2tuvvhrij.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2djterzod.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2vbsuracc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2rpsejwiq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2pymswinl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqqbosr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gt2enueyxcc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2dvekyvvv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2tawdmyge.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2vttpfmvn.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2zzojsqhp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2tlevamno.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2mdmcajdo.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2okxetavg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdfccmeh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2aemfbrvv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gogwbxok.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2plnpybmz.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpcphcbr.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gt2vqprytgv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2dkuvuvvj.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2ezqtrpfd.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gt2pwdpeedv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gt2avhayxpr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyksyrrj.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2vovrykjz.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2icxkbzxj.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsgrooe.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfjfrqpf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2ftwvzaar.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2jqunvtyu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjjkrxck.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gt2wsxzvdth.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gt2rqzbjfwo.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gt2nasfubuu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2icuogkeu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gt2vgmojmoo.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2gdkxncho.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2qlmmyiff.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2rvgfhmom.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2llpyazpa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2pybzzxvm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gt2zycgcorg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gt2nqwxwzcf.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2xtowojlw.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gt2gbaxdepk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2zrjztcyh.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2xetcsatr.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2ahvwlmwh.html


<!-- 参考信息 -->