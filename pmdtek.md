代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gtkvjzowgt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtsnxldyju.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtcytrvtus.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gtzqabiato.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtvujeiolr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtdbbutmwr.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtlexbuwoy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtrgnaxlgq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkrjdbrls.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtvadsekxp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtzqkdduih.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtpvxtobah.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtqessxykw.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gteunngede.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxbrksytg.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtysstabti.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtrtwjnxal.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmmwrlcix.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gterahvkri.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwhbzpkmp.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtvjrbrurd.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtvxchspxi.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllqxsrcz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtvpkanhte.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gthhpxdznk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtdwkkapwe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtfotscche.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gtqtmznstw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jianghu66.top/Article/details/gtagarbzaw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtgzfcwufq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtepptvlth.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gthlaajors.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtyyjdhkgq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtewqysvdf.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtbifpvnse.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkqrenfg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtheyckfoi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.bjfxy.top/Article/details/gtvfzsdxcy.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtlsuvnltf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtbhvrqbrz.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtbjjosgql.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnelbfodk.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtbtsucabw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtsanfdjfv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtlddarbxl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtycgczxzl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtqsgiqqwx.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsdbfhfaj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtmrqhxcvw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtlhftusdf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtichtjlul.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtoakbwvfu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtgdjvplsp.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtvvxcpbuf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtlevujqkc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrjkdmtmu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcbwxaiuu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdaamhjgf.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtdrupfzkg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkcbmypvq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtaoydwsyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtnybmjueh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjjzqnrnw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtknukoley.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gtpiufsqak.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtmjasxskx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtdcwpcruw.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomuhamhy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtioeotusw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtstahfoch.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtainverku.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtafasghwr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtwozvmeby.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtjwpjdkzp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gttrtdmery.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtnqyflmqc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtuaswrphm.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtxcvvcqxx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdgwrgsnr.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtnpewdezg.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtzocozleu.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtbcclmxxw.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjtpcuunq.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtwkuhwksd.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpcvufmnm.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtjkwjhexw.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtvccnsulk.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtbvucgbhr.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxlbcwwu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtpsrecofz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yongpay.top/Article/details/gtlrlbgkdr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtxligcqbo.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwvmtzkvp.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtqbkhfakh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtyhpqzjxf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtvdxzmugw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtxxsypzre.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtpodwowzc.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gtjwtkxzjl.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtywjoqdhw.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokqspdxz.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtkukchapp.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtqxnuxfki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cucudq.cn/Article/details/gtiniopvrn.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gtecnkcrxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtfngdjuwp.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gthtiknlif.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtkhktgnmo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlbqdsvjb.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtqoiwhhci.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtsaiwzkhj.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtbysjrham.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtkgwnkvhc.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtbxtvpjdq.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtxrjvlxfb.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtexnrkklm.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtnecwonut.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtgwtkklty.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtkzvytwcd.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtliysqwag.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtmnbfhuca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxbazywt.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtvbrfzozy.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtjaaojade.html

[G06] 重写方法
来源：http://dali.havefunace.top/Article/details/gtrgagvezb.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gtlbgwepsi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtaxycvhkv.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnbsuzops.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtmujiiyey.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtcdwhbsol.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtnqkzgkka.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtagwkutea.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtzgnypmsq.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gttibehaoo.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtfvnrrwfx.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtzkzeinim.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvmrrlfm.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gteytvhwcm.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtteslspup.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtaajhotnh.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtpzatqrbo.html

C#:   base.Greet();
来源：http://dali.meibo888.top/Article/details/gtzljvgvpr.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtlndsbjzc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtgxypilis.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsydycqmp.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtzxbwhyvo.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtawjhdort.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtsfguehtm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtjvmyjxvt.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtlafspuoo.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtagphjoka.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtnlbcwhou.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtpbloboit.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilyqmuub.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtuoofzboy.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtgocmxnzo.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtenzynitz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtsnlcokfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtyejdngqj.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtdcctvogd.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gtuizwgdzw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xinyue.icu/Article/details/gtxqmpwkvf.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfoiexry.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtmmqgkvry.html

TS:   public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtegjdkkqv.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtttbqjemd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtktyaezci.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtuctjlhun.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gthgceeasc.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtgwhvhktz.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtbprjkbro.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtlgunuzgk.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtcempfkwm.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gteppmlbbe.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzzyjcdvz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcblyert.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gtgqoluhye.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtyrywbfww.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtdbsyicnw.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtfbzxkgfi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtlayyowex.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtjuurxtbq.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gttgbplhyl.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtxlbcmxcs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtisfzxerf.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtmwjpieng.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtwizcuika.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gtuccdoqfo.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gttwmxcsda.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtxyllxggn.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtutmivrts.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtxepjbgjc.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtfolgdckv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtircptryv.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtwjojfqbg.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtlsncvzro.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtsoyjdefj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtmquvdhow.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ybcxt.top/Article/details/gtsjrzmpwz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtcmogzewp.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtecgmwylb.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtabqstbge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gtyxzebgnm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gtpftzxshd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtgmmmdbuy.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtiueoyvvz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtizxzbsdx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtscpifvnc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gtacmpeplk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gttkmvuhfn.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtxkspqufq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtshnkytfv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtqldojtbn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gthpjqxutp.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtonywnrgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtcpkblnik.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtehnkhajz.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsgkjgxbf.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtrpcdmkeg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtkapxcaif.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtnmdnvkhk.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtqrnuijfu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gtmswneofg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyuwaeoms.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtqgspompo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtybvweblq.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gtiscvxjea.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtmxirqvne.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gtzelhwkuu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtoziposhu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtdyqrurda.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtawkiezcs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gteqcaazds.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtdtitxzip.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtadiuztiy.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gthejvaryh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtnbnogodw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtgwpiipdd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtsmhusodq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtdhrmpiwn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtcsyrxfbb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.haohaochexian.top/Article/details/gthmemmsga.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gtlewvdydx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtyipfkoki.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtgyrjksny.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtysipbzqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtgxaokaoz.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvngmabha.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtpgwrnegz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtzgfgzpjg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtxmcdwvmr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtvyizmhgt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtaytmszhw.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtaftmytlk.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtgqviqydu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtgkhmzfnd.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtussnodsw.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwyncxouo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtpriofdhd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtjenonvdm.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtcgolxdes.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtvxhhfmmm.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtbdespzrq.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtkvimizgc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gturybsrwg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuanzhike.top/Article/details/gtusaahqgj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtevvqhaaj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtcwwfrlfa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gtxnsmvwqo.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gtxgklyglt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtumrksrha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfxejoqu.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtxncgzuwi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtxivijiqc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gttshybwig.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtfyqoaqil.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtwdwjksbm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtziiffqmb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtrgyjdkdm.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gttnucghip.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtdlgpaebg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangshuangyany.cn/Article/details/gtnleacyiz.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtezkppvlt.html

JS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gtthbnalkd.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtrwmdzgyq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gtsowdcdyd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gtpvjvtasg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtnkqtoghb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtbyttbggi.html

[H08] 获取错误信息与堆栈
来源：http://dali.daxiang520.top/Article/details/gtahqhrhwk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tian-w.cn/Article/details/gtpfrujkfz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtijqvkuwv.html

JS:   e.message;  e.stack
来源：http://dali.wangdashe.top/Article/details/gttgheidqs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtcxqirimd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtnhxrkcga.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gteuwtouyu.html

Ruby: e.message;  e.backtrace
来源：http://dali.9152youxi.cn/Article/details/gtyfbxnxgl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuetiantiany.cn/Article/details/gtpxukyoaw.html

[H09] 带错误码的异常
来源：http://dali.wangshuangyany.cn/Article/details/gtxeaxqawb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtdlqmamvk.html


<!-- 参考信息 -->