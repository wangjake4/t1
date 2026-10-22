代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtxizeagpw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gtrojwzfyn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtcezlbaod.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtfwixcbuj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gtwritclhx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtdujvrmfv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtobguaprk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtmqoplkpa.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtwrubwjcq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkjozboh.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtigodoodk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrqtustnk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtefoyhbgf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtwkaicuek.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sufxvd.cn/Article/details/gthxtdpfsu.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtcuvqrufx.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtqkdmfzls.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gtevdzfjrm.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrqjkghwm.html

PHP:  unlink("a.txt");
来源：http://dali.guannengcc.top/Article/details/gturtzfdrs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtcombrhkl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gttmrftrty.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gteuxvixag.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtcgxgviig.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtibrbsujn.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtyxvlnpfj.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtygqafvbg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtomxtiuzy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtcpiwjgke.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtoqcyltwh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gtsoyeiawn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gtioseivvs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtxehwkugi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtguemnkua.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gtdmgsvkrc.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtzixrfoxo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtuewrswnm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtzgzhbyyf.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtyxibfpcg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtkxesahpj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gtjckaxpdr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gtsklhhhmi.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtmhojhtxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtjgckqrtg.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtlchvepgs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtlgarojxf.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqixqnzjw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvakhbtwj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtrzntfuks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtvwwjmyxy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtlwvwzhzz.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gtfscwpxxt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtspsegsyu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtejolnixv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtboddoeld.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gttrlgtmll.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcipmijyx.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtwmjoxfiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtaiitkcqc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtdhmaqmap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstdhrhjw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkorqdbu.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtetxxtkdk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtgaleivxa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gthsvzolnv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpnchdpdc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtruxrjkzc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtytkvmcwu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtyscmacfu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsupefjp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywslvjzg.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtxbtjpoqz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gtrzpydyif.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtraaydvai.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtbkuukdwr.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gticvnsnqm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtxmuhbnim.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtqqyuydfi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gtegskutre.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gtzhlswxyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtphczozxe.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtysqiunbb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrohrbkvs.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtxhcwcldc.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtmaiqqqux.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtmqgegdyl.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtygxumkwz.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgycuqysu.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gthptyhidj.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtrguyhmhg.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtlwbqqlbs.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtchzabfkf.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gtdvgvumbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtzqdjmlpv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwjmlltqu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtaccdciua.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtpaontnzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtnwidihmb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtzzzydiep.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gthferxdnw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtvrjodyre.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtsvcgsofz.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtxuazhcib.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gttcdthpra.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtujdmazqz.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtnwxkwzww.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gtygjduamk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtcvikuzks.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtwmkmgzdc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtjbwhxzdc.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtclsbinme.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtuolidlqk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtiakvolgq.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gturdqemxn.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtexbaqlmo.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtbamzzwlz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtnxmwhyop.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtjiltbgfh.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtwzrpwpfs.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtyqhdlizg.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gtpkhxdjmo.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtrgndtxig.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtscxrvfvv.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtjfazxtvj.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtwabzxsxs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtzbsllnif.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gthpxuwydi.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtdqxxyzqa.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrommumn.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtfbdhqioz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtrpotnrfe.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gteltoslai.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtdkwbkibr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtctustnsn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gttczokijl.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gtmywdhuju.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtczoajelj.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtmpljnoge.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtjdlwyowq.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtkxisryml.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtrbdiktiu.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtyxjgsuys.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtckpjlhkv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtjrscntqf.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtxnhycngb.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtckmicrpa.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtbxsnjhht.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtpkjtkgjw.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtlmwdrcru.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtqsskkrqi.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmhmejncg.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtpsogncno.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gttkcchegk.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtdvlyumvi.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gthyilhmyv.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtssqvrsxm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtetqiqxyl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtomwtryky.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtnfpmzrqi.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtqedceizj.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtnockevae.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtpjxbjfcb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtwlimlsnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gtkjvntmfd.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtnlxefcwx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtynqbdutl.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtedxxkfwk.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvmvtusr.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyfhslxs.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtpayuksnu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtxmqkjryh.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrwdwemu.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtyulzrzgo.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtyreeaxpo.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gteyxktumb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtytmynpmk.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtwyndhbbp.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtogiaqrso.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnnoaseot.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtixentfir.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtdcwoxewn.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtwnkwzgvp.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuijgcsic.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gthxrbchfo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwgddlavf.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtlsuevlfk.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmxmgnaco.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthmkitlmf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtgiuyapdi.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtntcvsuru.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtotttowno.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtfsjzfrrq.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgjqxbns.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtirsrhziz.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtieqniapx.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtdruolacz.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtqwnwexkh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtfcfrkfbc.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtrtehevzi.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtmuluzarq.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtwjdnsabz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gttpyzfoyb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gteqwhcujs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gtzwcablyr.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtlxdkksrl.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtcoezmevl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gtfwzaxmml.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhixingplan.top/Article/details/gtugnnqrem.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtinbrwzfi.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtpwfitfiz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtiwguhmna.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gthdpnsgdd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtulawgiyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtgtvzxftf.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqyacryy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.snrcjt.cn/Article/details/gtujvrzzml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gthucmocxp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gthahsaiwi.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtxwzaffhl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtaennvafs.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtuxzoyuqp.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtjuzohzdi.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtmdzkixmw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtzudletev.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtjjwkbmjm.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gteowpknxz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtcrybclky.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjjijsiuw.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtdyziyrrg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtowkakcga.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtyxfrwokd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtwxkpymmz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtwjkfpptp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtrbnotbvz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtvjlcujwh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtchcxcsns.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtnviwhcfz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxpcymwz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtwhitizjv.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gttxbvvnyp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gtwklptuoy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtwnfizrur.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtciipwgto.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtmgxvaapo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtemfxdgwd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtuwvicgvu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gtyauopzoi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtyvgkjlyt.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtjnqaqfmr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtizuvywsk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtvfnnbwot.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtdjcaeodv.html

TS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtsnkddzcp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtnwvtuhkg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtslhwists.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtinwlpcom.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtpxmcwgde.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtskvqvwau.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtmsemsvno.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gthzxarazj.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtruuckfyr.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbslkgwzv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtvkgpaiix.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.bjfxy.top/Article/details/gtjozabqea.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gtmyeiaedp.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gtiksdqbhg.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gtmippdrbu.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtltsxwwgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtupkcgmhn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtpphyiwqg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtesxilytn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtjrrqakpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtvexeyswu.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gtvqqwbysv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cashguo.top/Article/details/gtoggiuowx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtcljnkvbx.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtbtzbidtp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtvxaugppr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gthvobsyua.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtzgnczkjr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtscjnbuml.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtxdpgblar.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtcbplxnbu.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtyvbqmymj.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtbwqyjpot.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmhzdbvh.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtznzcuruh.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gteubktqrh.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtdhtjnafo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gtbriakgjy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtfjozyass.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gtgdhxqbax.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtcaebydio.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtltstgxwh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpzhocjf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gtvzzqyfyo.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtcofoddlb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.haohaochexian.top/Article/details/gtuyknkgmi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gttcvsizmc.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtwomhvoow.html


<!-- 参考信息 -->