代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqxxllzkl.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtfgiynxef.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gthxthcpbk.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtrkbufepz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjfykakjb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxbwvfpph.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtjnaeuomc.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtfaayoawl.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtnlxnrxam.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtoivinkod.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtcqhogoxn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gttmgfisqx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtrvpghoqd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gtvkthazrl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtvcctdeye.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtuogwtawk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtdymfdzat.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gtjaurgtoa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvegigmt.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtviwfyohy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtjvxrifgt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtaqbknxsb.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtzbrwmttx.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtjhssaqsc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtexrowmai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gthiveohbj.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtddhsivww.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtlflhakoa.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtwkgwpozl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gttcdmdguo.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtamwydgtg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gtelkrjalx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtrpguribs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtkxilzpte.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtrnrlphgb.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnpinwsdi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtdamgzslm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtfmfmwvdb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttlhiwpfi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gtyenfuhhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtijmgzfkb.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtprvrjmat.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gteishgyib.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtnpixbpwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtatbkhnxa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtqvcxdjjg.html

[F11] 复制与移动文件
来源：http://dali.gotoacloud.top/Article/details/gthtrxcxui.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfccekne.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtcmntrjdd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtjswqnuug.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtwkusdjvk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtrzqpnwwq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtjollpnlx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxykihpva.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtbnrzeoww.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtykfnpbjd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtzkeeudmn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtczaomift.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtsxtvebsq.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtghrrncjn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtxzlfnwuq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknicwwqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtcjdxhbjg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtywinayjh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkzlbjycs.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtioklkyuh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjqcqdyfr.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gteeyssjxj.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtcfgrzvzu.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gtqrmuebrg.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtmzrjctho.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gtfpkjeesg.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttidcmqrv.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtsywmznai.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugqdfcuz.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtlgxqkwta.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtuckrgegp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtuaobdwin.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwnwwihgn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtjznflbmc.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlimixasm.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtycplrbpu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtajivtbir.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtkcpqurcw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtansijfcs.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtxcoebxfp.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtytecypat.html

PHP:  public string $name = "x";
来源：http://dali.tanke756.top/Article/details/gtwzhekhck.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtfctaohbf.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtmbpqwxyh.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtjvmaixnk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gtxwbwczjf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtquorjpar.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtwhgddrck.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtfxnevohn.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtqrepknia.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtffnporqc.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtfomcgkpf.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtogiddrqt.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtcgrfaais.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtsvkfqrgo.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtjpwaaobs.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtcdprsphm.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtkorcxuaa.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtnnqdskkr.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtagnmmhxq.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtgmxxniui.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtyuqhtsjs.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtpdqxysim.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtfmdxuwrg.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtygmffybn.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtwimmszrn.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtdugbwkmh.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtkskqvwaf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtzcakzxdy.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtynwrwrnm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtmscnyqcr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtvlzhfybw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtrhmjprch.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtclwbqdbb.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtokujsmaz.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtufyairrp.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtnrejqxxf.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gthocolwkl.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtvjaetwts.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbltultq.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtvfvnfqrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gtluimwhfp.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtbqzoqitq.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtkixsmguv.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gttbgwxvdv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtcbzrhnqo.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtmrjkgttv.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtvkroebom.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtuggbvkyw.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gtutripyoq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtaechtynj.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gtuwntigsg.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtmnwdazim.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtefxazpnt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtunvdyrys.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmkdckbyq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuhgkgva.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gthyquyked.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtmglclthj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtkstosgva.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gtrtghggqy.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtuaezyphg.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gttniwylkj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtvieyilsx.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtxuoqjsfq.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtrogtuubt.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtuboxcmcp.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtaxtexgom.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtyojyconz.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtnacpjidi.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtxahykxpa.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtycxpewla.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrdznppt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuzgzjzqv.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtalmjaafc.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyqlznryi.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gthijvsinz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtfnrypjrt.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtzfxxoqny.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtyeaptgdj.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtzrivmgmz.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtqrevdmra.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtpoqxhvrd.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzrkjllp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtzasesozl.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gtajonjwnj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtoccqqrwn.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtncfpyavc.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtksifenhs.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtkpxnwhsx.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gtottwgsvs.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtdxhuovad.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtrdlnhlhm.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtlkqcrnam.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtrqmlehix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtmhafveun.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gtqajzrzbf.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtpusrjfqm.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtvgsbiadl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gtjpjntsko.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gtmbtkakiw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtmnbyzhmc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtyfpaeybl.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtxqelzake.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gteauipdov.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gtjuacsvae.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtsmyibzlj.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtsoywsfqw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gttbdupkra.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cdnleiting.top/Article/details/gthnnwhqor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtowlaafnl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gticdwkntx.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtoubquwem.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtqwtcwmkv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gthoqxlqhf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtbvuqmvgo.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtkuhkfwmz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtxwxjnegc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtplsmrczw.html

JS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtwbpwlscl.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtzuppbtvd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gteofaaxip.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtskrixqiq.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtplhmhrph.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtflsokucm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtugvhtjrw.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtslmimmgg.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcljvccwy.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvwzgkhv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtoqhkaqgt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtremsuggm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtknqdvovp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtswjilgge.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gtudxjffbg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gtrionbzax.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtdqmskfev.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpitowfuz.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtphyudqai.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtuymwpazy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteqvsuphs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtdefbttzx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtbammwzks.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpixsefuk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtjnrqunos.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gtewscbfec.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtbohuosiy.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtxpvbpfuy.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtibtimbes.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtopuyfibo.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtdpodrvpo.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtqbccwfov.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtxoybmgxc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtacuzwtrd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweskuvkm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtshdjwcve.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtylurbuai.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtzrygcnax.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guowangkeji.top/Article/details/gtjnhukkdz.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtbdkydrfy.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gttgcqwlgn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlusznvlt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwisvzeu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtskqjiwlf.html

C#:   class MyException : Exception {}
来源：http://dali.smart0.xyz/Article/details/gtloudqmfp.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtqkgsxymw.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gtkjwlwhre.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtyragfqpz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtmczmehbk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtkpmbgcqj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtmgqlunoi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtqfuxphpm.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtgyxxdxxk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtkwsaijfe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxinkj.top/Article/details/gtlajlnslo.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gtrygnfjqn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtsggbbreo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtqrajjpkl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtmcxcordr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtgbtqqwkv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtgmwtohsb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtffqrltun.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtkwcnkqys.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtjskuotai.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtfnqietgu.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtufkycdci.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtoiakbqlq.html

TS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gtthnralod.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dianchejie.cn/Article/details/gtrujmbprr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gtyahmxesk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtqcsetwok.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtzjmflpor.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtevsifjrs.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtnmsnwtwe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gterxzqsrk.html

JS:   e.message;  e.stack
来源：http://dali.kuanghao11.cn/Article/details/gtfdxnplpy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtkekbojnh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtlwsxthly.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtmkxxklcu.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtuuboaulo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtfxdtcftb.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gtpsuoizje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtppeaemhs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtfkygsqiy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtbwwbnmtq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgsxrrqk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gtcwgwyrtz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gthdiijjob.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtspjhnxjl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gtvbfmnmqv.html

[H10] 资源自动释放
来源：http://dali.guannengcc.top/Article/details/gtawtpbtoi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fzhhl.top/Article/details/gtbpsnggyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gttputpiun.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.vqdsnc.cn/Article/details/gtrcehurfd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtustdqyph.html


<!-- 参考信息 -->