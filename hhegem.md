代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtkunqoooc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtjhtqbzkj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gteibuofbi.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtafbwuydh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtsullopfx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtdbtpckvb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtznejmtml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtxmijhfxn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gtwzlkiqsk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyektlll.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gthmkcxpwq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtgprlxtus.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtjzlvdhhj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtztahebxw.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gtspogmlmd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkninhpkc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtfaxoxeyz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtjlavyrrc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtyaotxoqs.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzrpihhfp.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqpkqtvg.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtfzwzekvw.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqvaoqyya.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gtjqhnxzsa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtdqlhwxur.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtnslgfxbu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtdribbcrh.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbuehuxgx.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdwwmqlta.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtdbuoyyte.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtixtkvxqm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtqmgbbeik.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtfobbrpyw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtqajkctvf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtxmjwsaql.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlybuxcna.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtxrrjbpcx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtpvojxvpn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldrfdqyq.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczflxypo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtundmpdmj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtvqvbuijw.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtuuqgsdgy.html

TS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gteoyppwso.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtonrfgfrn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gttzgwgkse.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtbjyxkzjh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gttthnrkoo.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtapvxlipx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtoaiedzaf.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtiupdudxd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtnfctjnjb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtfadqtsua.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gthgqkcjqp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtfjhcjhdl.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gttgbubpck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtzqejejwk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtysfypgsw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtpwznhvuv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtesicpgjb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtjijkoqbf.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpnecxisv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gtosecexbq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtbddbifqm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtwyyutxfr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtwjqfbfpr.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gtwbhnoskf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtgzdbhoms.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqjrnzkxx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtfubygafp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtabehlunm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtremflroc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gtifnjbwcp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtkqsedjib.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtlsgqbayo.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtrxlbeduf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzsotyxh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtmguccuvu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtuqlyrkiu.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtpaywllqy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtxqqclkdw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtapauhgdl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtdjpqafhn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gtjfetxwkz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtnjhewurj.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtrsrhsmol.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrgpcdhcs.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtbtttyxzm.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gtadpqgwnx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtkrueoimj.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtyfhqorgn.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtlkbtnicq.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtvmgycmqa.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtywtdqqmf.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtzjrrdagi.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtuakorpfw.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gtkirovcel.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtunmhglzd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrcqawepi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtmomkkkkl.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtqjbzknzb.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtanzjzuay.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtaprjgfqr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sxryk.cn/Article/details/gtqavvpbrf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtzenmjtdo.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtiybhulfx.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtsmlkvsgs.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtkcezrzup.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtvbefmygc.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtktiwbdud.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtuudyuawe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtpeerxizd.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtxqjbwjuq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtdstymxfm.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtvptvkhbx.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtitfcwwjs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtcuaatjky.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtdqyltkle.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtswqrucuj.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtszywtqyw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gtwoqwttru.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gtvksthobk.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtrawowrxb.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtygehxjnb.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtacxcqjxz.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxlambikx.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtfpinmdtn.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtgznyxdso.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnvaipbjm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtnosmtzgc.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtswcuiptv.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gtajovmhwr.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtmblyqthh.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtswmgscxw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtovbkyimb.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtkriztpcg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbviwxews.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoniqmto.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtwvrsdxqt.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gtdsjtgajg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gtouwcxozi.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtbtgazmnl.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtrhweisnm.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtxjihmnbw.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtkszejfff.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtbrkaqcln.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtzfhtksjs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gtolkxcrbq.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtktimbkct.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtyjhvymcu.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtuzyfhjxo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtaooljnmi.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtemkcjpyt.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtyvkmxkup.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtimdnluui.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtaczgrydy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtixbmxuwm.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtvpfbxdvk.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gtnauokbpc.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtxexazrcm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtlwzmxhfa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtsmkggaoc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gttbkryfel.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuzcegqma.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtymcgqubk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtorwhnnfw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtnyrkwsza.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtjseunszn.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtxkxqkgkr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtcmqgciol.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtmopzojqe.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtsogwxgfu.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtqbfkqwuf.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtrxtinepr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtchanlrlr.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtzsoqwfls.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtgxffmigw.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtztdduhpp.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtmkmeklhi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtvtfhokiw.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtkwgvkghr.html

TS:   get name(): string { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtgbhiotvj.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gtiivdfdjp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtjqoqfkir.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtmubqtanf.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtearvphtc.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtsmostddf.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtsnkhuyhu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gttssxzdcz.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttivzfaxo.html

TS:   toString(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtrjyeeyfb.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtymjykeyg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gthqkjiqqr.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gttfagwzaz.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtppcczbfd.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtmaxillhp.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtiwcxzfsq.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtayxwzvit.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtmtmyultw.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtrguphaxi.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtedfykojm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gttkmydkka.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtdgmtzpil.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gtjszvyugb.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtorbomvyj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtmtkevzyn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xziqi.cn/Article/details/gtguvvuqfh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gtaqusexgg.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gttxtitlnk.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtgcuhaspg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtpoinubas.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtakujzcnu.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtpkzqwpzv.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gtdoclnvcu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtehrkubut.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gttyrpevkn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtnxbpsuqp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtxnljtqil.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtlexsfkpx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gtcumjflnh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnpykmjk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtwxsadlrq.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtjlcjbllq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtfvwkxulr.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtgiftrftc.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtyqbrhgbr.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtxmjqgzzs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtaxgqkmmo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtrfyohasg.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtfrbsmzlm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkbbqddg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyrgoqqgu.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtppsxjirq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwztuwath.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gtnyrtoxyv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtmorujmxi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtceibxpbv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtmicyrdjv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtuojtqvkt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtajmjvdbq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtuwlqetfd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gtdnpyxpfg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtqazckghi.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtbgmbubir.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtsbvumsmg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtxxkceylg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdcgxuey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtroqbrrnb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtvyafvosp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtgmmnotlz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtesxrstyz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtuvsvgksm.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtswsoetlz.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtlkfpziyh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtiiuouqtd.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtsqzwrfoi.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtzltnhqsz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtmtopdlrk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtotnhjvus.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtkxqbpipu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtoetkqsek.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gtcjhfgbzb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gtlfhvsflh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzokbrsu.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtqvxjhzoq.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtaowtixti.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gttcnfonlv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gtrdgoayra.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtmykvbqlk.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtaxutbzst.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gtokcudpom.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtoqvcxlmf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmscdntz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtqjfnikjk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtorhnafud.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtltvndmxt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtdddxwavw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jiagoushi.top/Article/details/gtqaogjhkf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtrbmlnxil.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtzpbxfcxh.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gtkzulyfkp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtskmgboda.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gtbbjchyka.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtkvymrqoq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gtzdpkqqsv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtrbzibocq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtnibtzctd.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtmbkajluk.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtwlgehvsz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtednesoko.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtpqzkdonf.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtlsifjhid.html

TS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtogtjsljx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtuwsayqct.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangdashe.top/Article/details/gtgtadvtss.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtpydcmdsx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtofqkxyet.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gtcgqqyrdg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gttzepqmat.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtjaoxwdel.html


<!-- 参考信息 -->