代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqvnovxl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtckymstze.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtztquhlpe.html

[F04] 追加写入文件
来源：http://dali.tianlin.xyz/Article/details/gtauxafrzd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtylsgvkdi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gtlgnvkhcz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtwkqzsagl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtekijsjcx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtpuknigoo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtfiajxkdy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtvooiiksm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtbzxnabph.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtpjdeupfh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gtdhpvjryc.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtwtwhlkzl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtwzxpeerb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtectzywss.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtthelyeph.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daxiang520.top/Article/details/gtwhaypvbo.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnkxbkvet.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtonyibhka.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtxqpuowvj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuidhencj.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtzplbbhli.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjxfzecqn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthocbbruk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqxvwfbg.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtmjkytbtr.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdecodhha.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gteyrzbtbv.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtfgqzcuae.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtokhwmriv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnaiijeul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtgcvmmjky.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gterlmhahv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtnmmaykpj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtjbqmasop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtrdfrollw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtfgtuuqbw.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtcslaqdah.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gttcvvdouq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtljnpynbk.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtpfkmooel.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtfrfsliwe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtjpaqlszx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gttqrmhgie.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gthqquitzd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gteawnnrdc.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtcarfgwvc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtvglcmeww.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtvhpkpeiy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbwswywi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gthkmjtfwb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtspsunhhj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtloqnkjjw.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdbpgzfob.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtdgefsmhf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtnizunyts.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtzatorzns.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtfbcclzzb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtwwrecrqt.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxcpgdicb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gtbsfawexz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtuyngtits.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtlzoavnqd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtamzlojly.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtxsjjektk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlnudztow.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrcrqujed.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabnckbcd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtytdserie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtaqgjmfyf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtxoobddlf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtenjnbhhv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtdnpmwjtd.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtqqxkajjw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtjvcsjcas.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtujdvahzu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtfbhtuecr.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gtlkwwluma.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjutidkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtzkizgimt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gttaloglwx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtxjnhgnpv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbcjsgvjr.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtryxieekz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgokhbisu.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gtlspnkvtg.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gtinvftprg.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtqfvhhqhp.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtapqzgnnb.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtubggowqr.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gteafpnwdw.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtlrlzmlpt.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvxwhkhfo.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtqiscyuoq.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gthqrxcnin.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtzdxgpeze.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtudbxbzuj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcloqyvnv.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtygbqrwsy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtndtfhdub.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtzyitmxip.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtdxxibfra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtrlgptvly.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtxismyidz.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtognhzjtj.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtamuxxznw.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtcyadjybx.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gteueiyymy.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtwppoacsd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gtlrtqeale.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gttcwledhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gtormusnuf.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gttphkrkzo.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtjfiykcnt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gttqcfxwkn.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtqpdmnvuj.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtgqtvozef.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnzblycab.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gttncsqybg.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtkcvwnutc.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gtbslcbyqt.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtrshdwzde.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssvdpptt.html

PHP:  class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtxqqdgovh.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtsbnategv.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtygehioow.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtyndmwgqw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtgznzxyey.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxanqals.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocbpkcmp.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtnhpxqmcz.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gtrqbhrtuy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtvbomsbtd.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gttxsnkieg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtnggijkau.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtjcntmdqw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtwbxcnwdp.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gthzyqwigy.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gtmgbnvubw.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtcdibjeft.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtbmyipqsp.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtigamerbl.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtkeztttak.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtzwodtsan.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtvenayezn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtzrncnjgc.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtjvvqpxbu.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtybueixft.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtujpxnixb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gtobkardfd.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtbwghadzw.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gtvkciqizr.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtlewgjgmo.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtjatdglij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtdncdoyfg.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gtxyohnvmv.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtmzedspau.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtwgdwfqpq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtxtyrcetd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtlxdfbqkn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gtqpvowzvp.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtmjreltfe.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtekwhijms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtgzjkswmy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gtmjpwopmc.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gtzkfezetl.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gtiuibfvdy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtupojebdz.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtwgndxsth.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtaayhfazo.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtrwbdwbku.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gtxzmyvrkt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtetmcfpwz.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtwkeqwcjf.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtqdloeqdi.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtpxayxkzl.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtxztajftj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtudafhnwy.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtjrtxezre.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gthejhnwmt.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtvxqrhryz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtxkkqfrad.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtkasvofoa.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtrrhxvams.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtbyeokaji.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlseapjfc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtjsbzoeon.html

JS:   toString() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtxslngmyc.html

TS:   toString(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtimhhwifi.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtjqgggdpz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtuhbbovly.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbekylswy.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtdlbuwzqe.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtwuvdqyfy.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gtsurrulug.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtwbhlduvk.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtpejhlkrw.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtuzdnrwes.html

Java: u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtoywwqwjt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwgexrbm.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtfwjuazjk.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gtfykljjhp.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtwynxyhoh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gtidryqekq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gtuqgbugit.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aizwys.cn/Article/details/gtzntzxuhj.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtanwngbhw.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtfhofyoei.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtfnpyafqp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtahumqmmg.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtgurithcc.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtdaevvzsc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtylmselgq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtkwbuvlzm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtpmuyxfet.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtriemqwhv.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtvmsznsdf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtjmixsqfo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gtyfynpkhz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtvpmakyav.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtooibwpjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtpwczrjfl.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtqkmmhqyf.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtksqjhxfz.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtixmckqvj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtpavijtgb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtomgcbrxf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtgfvgtrtr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtsabwioef.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyzpuiynf.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gtdkqcxxrk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtutmxlrir.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtficparqf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtdbnjojtg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtcnqrxxoh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gtvrgufoaa.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gthfusgmpa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtqevtzvze.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtxcwdefdj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqesanywm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdlsdiru.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtzmdpjsaq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gteonobtai.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gthzpntomp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtprcilfwm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtqvpgunyd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gteruzpoui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtqwzhjuvs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtdrdunexo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gttjtkmpix.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtqqifijjy.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gteobiptoa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtlspusjre.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtumnvxzvd.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtadjoyqas.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtyjdscmkp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtzilsyfaa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtnuwqolbl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtduzprzzc.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtfsbylhhk.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtebnbgjpj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtpofddjta.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtbdrirhud.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtmrhgiowr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtntxhoxmp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtlzkpuixg.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtibotfuuz.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gtkacwuaiy.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtbjpkftok.html

Py:   except ValueError as e:
来源：http://dali.9152youxi.cn/Article/details/gtfjrcndhp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gtadjhjacv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtsikrlduz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtdenmxszy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtnozbqvye.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtfimbrcwv.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtbmjwffav.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsjqifqzn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtzduslvma.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gtimhelznh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtqufdyeba.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtrihbrdko.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtneypdszn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtjleuyvfm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtqvqldkjj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtgwnjbmue.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtfihicnre.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gtcpftomrr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gteopcruse.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtxorsrljp.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtuwlisjbo.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtaecigbdt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gttvibkgll.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.kuanghao11.cn/Article/details/gtgeadacjp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtupjaopku.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtgsutvwhd.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtrlifyiax.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gtubdsysxy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gternfzllf.html


<!-- 参考信息 -->