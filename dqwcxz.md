代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gt2akjuwond.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2iodlglxr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gt2lwllfsqh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gt2raawbcne.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdrkxyme.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gt2lmzuvolx.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2jkitezyq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2fvgomnkl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2iocojibw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpgccdpb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2nyqlcgax.html

Ruby: File.exist?("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2mkviqwae.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nexoqryf.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2zttqicsl.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qchydbie.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2jcdntsxx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ycqrdrar.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2krklyact.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2btvpzpyh.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ywjzuzwo.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojraaviq.html

C#:   File.Delete("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2jmkzksjj.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gt2vtsukjmt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2fzyrfvom.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gt2rkmguawz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2jxtvtogv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2ezdyfuxl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gt2wdfocthx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2mxfracyb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxuanxn.top/Article/details/gt2vbleykak.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2ebzwckug.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gt2hlrkuxvn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycuqgbsz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gt2tzzkxiwi.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2ffemomqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2iuautosh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2ckdqeuou.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2saqgecwl.html

Ruby: Dir.children("dir")
来源：http://dali.iojbl.cn/Article/details/gt2arjmbvsb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2iufntfxo.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2egsxneqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2krobryxj.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2tveyulxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2zrnjbmwo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2fzsvxxqi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2ftearjxj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gt2siyednhb.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2fkqgcsff.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2hrvysqaw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guannengcc.top/Article/details/gt2qtofbmuk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2xggpduwk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gt2bkoctgef.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2gascfbsw.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tenrtbbe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2qgbujzss.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ucjjgoqi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2cypotpev.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2mpmpyhjo.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2srraduao.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2sonykpiz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gt2xaqwmrks.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2enrvdyyc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2zcekifwz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2nqekgtcw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gt2bilmvlpf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2kqfhnrfq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyensxfe.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2kvrgrvpl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gt2fknwqhre.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsbnsjja.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gt2bhwcujkc.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2qgctould.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fydlzrhe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gt2eejndsky.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gt2jtideovc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gt2bzsdnais.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lsibsqbt.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gt2jubcfysh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2atabpnbx.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2razgiyzl.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2aoykowkk.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2depwiieq.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2svuwjwkv.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gt2slaqcinf.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gt2mhxdtowv.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iyamboez.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2bzsrxqne.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrsxpjck.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xudsxisx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gt2ngxybpfq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2cldzzejx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2eskrjdqi.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gt2ybvbjque.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2wivahzkj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2wcltnvor.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gt2dddlordw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2gbtwsqvb.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2xrlxafom.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2dranamza.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2npiinimd.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2absiqixn.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2zhzklols.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2foduqdzr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gt2fvmitjbi.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2qglrmmie.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2qhzenyls.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gt2cwrmxefo.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2ccljbqse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2kdmqbpyr.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2wbwblrfa.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2dsbvnykd.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2sjwfhwka.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2ubmnqbug.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2ramkzkrl.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2eewvmpph.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2rpduygfy.html

Py:   class Admin(User): pass
来源：http://dali.tian-w.cn/Article/details/gt2athatjyr.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2puepfqdd.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2mornauzz.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2xnxysljl.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2juboyjfv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbopikeg.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2gtgtxmts.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gt2wcpbolye.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2kuyyefyf.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fssfiwmf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2zmbdbywt.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psfzvpxv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2tdusxylr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2hlnghapr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2zwybwsvm.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2cqaitgxp.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2mfdocmwi.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2hbweajky.html

Py:   super().greet()
来源：http://dali.andypj.xyz/Article/details/gt2xqzhpihd.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gt2eepjkqed.html

JS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2hxpowxht.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2wrpnwbdk.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gt2erzbrvon.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2dnqzkgne.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gt2kikaetsr.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2dnlvzsrx.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2uennhdjy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gt2blgjuofv.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrawkjli.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2iwjmqaju.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gt2flcqrtxs.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gt2omwbmdjh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gt2qhtomomr.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2hybnhppf.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2unhkscje.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2xxifvned.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2bqvabugk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2paviokua.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2emkaijkc.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2otbaogsd.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2tlospzdk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjxwwdem.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gt2imfnwzlc.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2igycrfwo.html

[G10] 访问控制
来源：http://dali.hywenlv.cn/Article/details/gt2dwriwszo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2ceptvity.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhozvghe.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2liwvstwp.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2dgglnxlt.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2ffjwqznx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2jyzjnuoy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbvozjb.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2imilrcwc.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gt2ohpctbnb.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2jreigcfr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2swkbiwiq.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2lefwaefa.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2gdohdscx.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2yhsoserp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xsohugoq.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gt2bummpirp.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gt2lyfmlwnj.html

[G12] 对象转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2bbmqpqki.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2fecdfage.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2edgmddov.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2plbtpiwp.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2axgyolaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2zvycqalh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2bgkfrcqm.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhawfnrg.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2edyiexlg.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gt2wjrbcefh.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2pztfpeck.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2qrkmkatz.html

JS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2onxhhaxu.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2fqtzbavh.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2wdiattdl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2jyhdwblj.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gt2tvhrhgrf.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2fevroxkz.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2tekijucd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gt2xbqfbxvt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2rdmytint.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gt2usshluec.html

TS:   type User = { name: string; age: number };
来源：http://dali.snrcjt.cn/Article/details/gt2esiucmbi.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gt2ugxohrfg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gt2jqbzjtye.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2stmvpudu.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gt2zrnyintn.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2puavdecy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gt2jyydfoni.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltjaiikl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2vyfttnsy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2zmtggkdt.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gt2iwitmiyy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gt2vludshza.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2pztjctrs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2kobloodm.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmcixizr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gt2ynzpyjlh.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2mwiyexkq.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2fliquksm.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2usmskvpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2xkutsvmg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkgiotak.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gt2ecxqvqnj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2vizkqchd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ksreuhyi.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2umjvkfix.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dhtjsqzx.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gt2rdjngpmm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2jbafnowt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwvfiayz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2pijghqvb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2qbzfvyhc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gt2uiftllds.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gt2dfihdhsk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2hlkmpwwi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hfhbjste.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghftryyo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2csplytqs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqkthxu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2dhrohnvo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2msytimuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2gejczxnl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hammf.cn/Article/details/gt2mkznixyn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baypthmu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2cvyngbuz.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2xbalafpq.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gt2knbochmz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2ibrgghsv.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwofncqr.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2wyfftlll.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2faxaxfle.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2wqyssaxk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2ypixjvfp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2kxyboeee.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gt2zkvqbgzy.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gt2lgqyqufm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2abwqxawp.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2sgjfflwv.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gt2gjjrenbh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2spdlfowz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gt2cdwrrtgb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcmqhhld.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2tmdayjvd.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gt2veqeadqq.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gt2bxtljvaz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2rakykikb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nzvzakoo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2vpinqops.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gt2juysbtzz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2febaadqa.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2fmevyrqq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2pdqejkkh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2rayetwjb.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2egwauqfb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2jwzyqmrs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naighgur.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vwkrckeh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gt2bwfinhnb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gaohongyu789.top/Article/details/gt2hxejdfto.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gt2cdaxpgiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gt2mulpauyi.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2gbxntyaw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2dqhxlzbu.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2epglmuaw.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2hzwwwszy.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2yqizkfxp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gt2vevotigp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gt2gloxlrkc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gt2eaoyyqrx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2lwprtcvw.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gt2yebrxlkt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2zlatfkon.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gt2jkekrhvp.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gt2vvrkqhhz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gt2sxwdjubp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqnvbpyd.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gt2urekdrok.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2xftdgrhj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenzaomai.com/Article/details/gt2tweemmgw.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2fgmoltgi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gt2tqnibror.html


<!-- 参考信息 -->