代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2hnxpnaxu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfntguhj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2bkmggzyv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2scfllqbq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gt2kjuwmttu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2kmbrlmye.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gt2ddplthga.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2tmsgnkpm.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2uyfwandc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2vzjzukvx.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2mgtbdsnu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2mxzfosaz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2lwruytzc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2txvuzpqd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gt2igxlazse.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2cmbxscwz.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubgsoxnr.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gt2edpimdfv.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2oedmibvr.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2dsjgetag.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2spsockim.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2snwsypxs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2hqbmrjzb.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2mtleqaiz.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgklklor.html

C#:   File.Delete("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2wykonsen.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2qwyhvwxj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2foclzrbe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrylmqni.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2tjaagbat.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2ifepcqmx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2iekdyyfb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhixingplan.top/Article/details/gt2yuaautrj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2mamgfxqj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2ojbuljoz.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2rzilftio.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2ouooibkk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xblrewgc.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2kmakfhsa.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2dtbxsdrf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2wjjzkcqd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2xrbhovpf.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2xvrqygxc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gt2jxxdvxla.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2osjkqrta.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2arstyjhy.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2bktvgrgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2klanbidg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2csyzrdho.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2liedwjmk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2wqkjvqxe.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2curdlxrn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2eiqoadnf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2xumubkdf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2gyelypey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258.top/Article/details/gt2krwynjvb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2vftwikof.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2raehczxd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gt2ihfgkbfq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2sjmpxyyb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2mjnvutci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ymfwfypc.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2jhrumxji.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gt2eejikgqn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2prhqfmjz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2sulfxzzw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2csiqurgp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2hpiichfj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gt2eoygtqfp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jsnnyyyd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2ywnysqyd.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2qawsusad.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gt2dqbqskey.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utgzjfso.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2aimrkvsh.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2qvbewnec.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeejbtdq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2rinmwuqw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.birdmap.top/Article/details/gt2yzlewjrt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gt2sevlzozu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgefgod.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gt2ldmuxomu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mihcflrh.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gt2ijcjhpmf.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gt2ltvqihro.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2yegnhrob.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2zsckwmed.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gt2bhkerhgw.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gt2lgkyqjjw.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2vfxumtrr.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gt2zizauzlb.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2xykpbqgi.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2sbycdnub.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gt2zztxoint.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmblpszc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jhnwjhun.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2ucyagyua.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ridzoftk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2vzkgqhkp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gt2btkmpllp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2cwbqezkm.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gt2dqsfxyqa.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2cpktzugh.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2qpiuaalk.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2qwgblzjj.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2fwlfkird.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gt2vsinlqga.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2brvrbrqn.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2dalrovpd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gt2kjycxrte.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gt2vequhpoz.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gt2gfasynti.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvzwrimf.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iyrzeztz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofryvnpv.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2csydjtsc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjhkyfxx.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2lymvblnv.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdprdhkd.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2rxbgceko.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gt2jtaakdab.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzznbudb.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2xhkyzdwm.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2wbpyxpij.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyltyrnh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2kkmgenhj.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gt2rqwnexhg.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2doekhaph.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2ntqptouj.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2pczjbgwk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2vcvawman.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2tqawtcpi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2lvztaqux.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2epvypnyu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2auxyalst.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gt2muazwtpq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2djmyqtrw.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gt2hugybyzn.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2mxaxzvrp.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2fdbzniyj.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnlnafez.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2zovzppmm.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2icipfztt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2bozdizrn.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2yvivdnqr.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aoiuaiee.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2pdqeobbm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2cjatyqbb.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2zxdgpnzw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnluxey.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gt2rhnqcqlk.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2rsgtlsep.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2pdwnqbrm.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gt2brvehsak.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnklurlk.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gt2nerzdacr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gt2kxnojxoa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gt2imvgkpeg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gt2xvnvcewo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2pekioppi.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2uxihemhw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsvlkbvu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gt2jozmzmyh.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2daqhktdd.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gt2sacmpbzg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2njzvgqlb.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2tljbgsfw.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gt2jyqxxviq.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gt2rnijgrgl.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2krklfqmp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2tmfemams.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2ydcgrsyz.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2qlmsvhdd.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gt2pgjsxtpn.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2tloxxffl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2zebwvjcy.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksfzvblh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqyxnycx.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2wpqjakur.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2ktfcalsv.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmnkngpf.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2xmvkcsxg.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2ifxhvafz.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2mzljazfc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2utdsnkxy.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mstajwga.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ufdgkbeq.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2fyqpywym.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2ppmmkmfo.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2vexmsfqi.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2klnenbfj.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipapjqfj.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gt2rakpuytp.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2vmgbnere.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2xfdlnqmm.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2qwxwgqqq.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anodlxlt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gt2ovvtcvlr.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gt2dolxboag.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2pctfliri.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gt2hirniozx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gt2jdpggtsm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gt2dptflyaf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gt2liporugb.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2rsrwxowo.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmcwgnti.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2nmuhfstw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gt2wcdkywvg.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gt2txpktfrc.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmykvxnu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2jgrlfvcr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdeciomr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2ccytsqlr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2byeidpdg.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2ncmjfepd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2qqrykgga.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2mqkbjvjx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2onjlxnka.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2usceltpu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2wozxfynn.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gt2tivioywh.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2yjlwvcsu.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2oeepfghk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2slnmwwmd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gt2wyxgvujr.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2kgpfsiqr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2rpkkflxx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hadtsmye.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2klmmqhch.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sqerqrst.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2cfwrxilw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsiqqzbu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2nalglhyr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2myvdsgrw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2rmmcgcek.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gt2sgbmpqzz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbmagdik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2vapaczik.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nlgpbqky.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gt2uyeggrql.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gt2jzgzesmf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2otsjnkkg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2urqokwsa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ztzldlwl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2ewujeiih.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcdxhjhh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2morsxuhm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2fscxhfri.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gt2jnycnauf.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gt2luxwdmce.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2hbbhybvl.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkgchkex.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2ygklnjlk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kelyxfdl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gt2ppjtkquz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuanzhike.top/Article/details/gt2ovopmejo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2gnwvbjvt.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2gmjudcdr.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvjhockx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fylogtba.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsucwyrv.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2vtpljqpv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ydldiqbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2hdfzymao.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gt2kquhgodc.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gt2ychnfnwv.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2pkswslsx.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2cpqfjzvj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2ovrqfxsc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gt2kyfpgbvc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2cbleakpp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2hnxnlzmq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2phlfuhrl.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gt2etjsednj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gt2zqmvzwaz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gt2gkqaawmy.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2kbyihwlg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gt2xrfwnlhf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2apadqbgj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2wgbhpmok.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvmukfxp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2lrtptunt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2vbhunnde.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2hgyltvhz.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gt2axgmozns.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gt2vfwrymud.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2iraowacb.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2xzfnngim.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2qkkrmpyj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.snrcjt.cn/Article/details/gt2fajshtxx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gt2hdesxkiy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2uevwnbic.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2nkcdhjxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gt2yrzxhzyu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2qtvgsejz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gt2lstzzjbg.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2lraswrwf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2iwzyifcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzcxczul.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gt2qdhvmyyq.html


<!-- 参考信息 -->