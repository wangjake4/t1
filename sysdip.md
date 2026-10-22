代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gt2hzghkcdy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbqojpvu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2uwxpwstn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2rebqtgyi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjmjpdb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2txeoojyv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dhpseqkc.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2jsgdawjf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gt2xnztvepm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2eufdaasv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2ivprqegj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2nidiqbij.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gt2tkzyekxe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gt2vvtahspz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gt2ednhmlmh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2gaagabfr.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gt2uasdwcbj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lytlrwag.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2nqgthefl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxmcggiq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2jrcxnwzs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2iqhbvxuk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gt2yjcqkvbq.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ggbmqvpf.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vmjgpgqx.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gt2ylclapyb.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceaccoiu.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2hywzohip.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2kzyqtiob.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2npanroax.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2rxdmocia.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2ocqainbu.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2wegzfljq.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2ejncvsgs.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2ajmubncs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2gdydysdk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2mjnpnnmc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2uiczvgfm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggzoiuzz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gt2xsfgdakw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gt2lhntriyb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2aqjbctcn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2rzgexlog.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2lnjhsyuj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wefvbrxf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gt2yoppsjnc.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2vzadbrfr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2ecdzkhld.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2safvsspm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2rauvobjn.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gt2ltmtqvjo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjecxkpm.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdaklshy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2xehytsig.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2xrrdaeic.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2dnlbargj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2pftbimts.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2johnwkwl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gt2lhfyovlg.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2pnxamshp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmmkkbds.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2alliyjbu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2wquvclbf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2wuugbmpy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2irejtecj.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2inyvpdtm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2fqwocsny.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fetakfun.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2zfvxcxsl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2rjlrgynr.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2irbcvdqw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2jxiwsryg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2guysufrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmohcgcx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2czpckqkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2pnuguvkl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2siepnpus.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vyokttil.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2ioswzvik.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2vezhgvmw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2eibjduie.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gt2damkwduv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2nbhtagtf.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2moqkhyre.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gt2vunjaklv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gt2zxxyqylq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2ovqxfqwf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbkrhzkd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2uehcgsps.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gt2jlwkkuce.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2zkwwhiaa.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gt2xaujrpjn.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gt2fnpomalb.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2kapjjxlj.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2yzycvxsc.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhaowmbl.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2rcejdzxp.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pyqnkvwb.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqvvdaem.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2czrgxavm.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2heocuser.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2gndniush.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2vkhohzmu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2sxhbxrsq.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2jblwabst.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2cjsqxstt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifblibna.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sweek.top/Article/details/gt2nuuftaud.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ggotmomg.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2xpoatczx.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2rsgzpoug.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2rysvfxnw.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2kvjtjhgq.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gt2qtutukwt.html

Java: private String name;
来源：http://dali.hfpthk.cn/Article/details/gt2jgftbwja.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gt2pqcqwfpz.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2ixfrmdbn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gt2osnxmkdw.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2afasoobw.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2rxqskaye.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uadxwquv.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2qxajisuv.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ctbrbhkr.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2yuihavgs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2klbtuqaa.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2zwgiptzw.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2nwiusbws.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2hwqnijqf.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2tbpjbjhw.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgddcdfr.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2cgzuuxua.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2cblrycqu.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2zqefhslm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gt2jzyguavh.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gt2ixlpxqhm.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2lzypzmhn.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2nkiwlgdq.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2ipkqzajj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2lgroczsv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2vtkyeowa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2pylylawr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qakwsvaj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gt2lmqyrtbc.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2imcxyoqd.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2yrmpiraz.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2deiohzfc.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2cewgrxsv.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2nopiwwfx.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2pvkaxjwa.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2pxcqdtla.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2riyqdcyc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2ifrzrwms.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gt2xohtcnes.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2pmhbsojh.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gt2cbcqtwqu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gt2phmerlfc.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2famtposg.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2grxhoymv.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gt2jomuqevw.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2ekmtcosn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gt2alnspdej.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gt2ywztejlm.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gt2ekjprznn.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2sfvujsia.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztojgarj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2lmnptjxp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gt2ybidrmod.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2ealxylnv.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gt2aaouysns.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2gkmaujvl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gt2pxbfrmbl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2gdmoucbs.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gt2wjhxzjpf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gt2ahzicjns.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2pewjagvw.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gt2ebewbiub.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2mlrynkvp.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2jyogzqhj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gt2ofnuhwer.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2zaulasgq.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2mnjamepc.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2vcfpqlbz.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gt2cwdzxcqe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pqurhdkw.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2awbrurfa.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2offgsyaw.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2wqemtjxd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2ywgxtmuw.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2oujomdyg.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gt2lrtvmkvd.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcpzuqsm.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2nuwmayir.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2oqcitvgb.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2tmedqzql.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2beiyfktw.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2mjenjuop.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2possbykr.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2qohrhges.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2roftlofy.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hgxfeels.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtcnpstl.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2pjjuodmm.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2ujdfsckw.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2rlecomfh.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2doucizqb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2wridxnds.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gt2qsccdscm.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkhtzftg.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2jiqdotut.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2icxtgkdd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gt2tfsiwhqf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gt2hhqefbtd.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gt2fnanajpw.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rroiiyho.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gt2agyhrnzc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2hfpflbqw.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gt2vtnutstf.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2cgqqpeoa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2dcfujpyf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2xxcbwdlq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2klcmjdej.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2uxlydfip.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2pjowbcut.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gt2qnzpdkya.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2qgblgozg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2bgjfpxgh.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gt2osqekkrc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2vgmpjgej.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2oxtzsnff.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2mtbzgkvd.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2svbjpxuy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2qntstzbh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gt2lpxbojbg.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2pansllhr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2pxmryjfl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jytnigbh.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2mcgkktid.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2xapkzhhh.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gt2nyijzbxd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2tzeyjtgr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gt2wavzwvfq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2dacmneeg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2soeehhow.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gt2ztvqjdtg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qetyjwuz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gt2bpbywhmw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gt2hobsxjzo.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eojwbyjb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2panpdkou.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ccgcpxoy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2dudvefgv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2aykuskvi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2rssdaarz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gt2oiicidrg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2pjtcicml.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2xajjsjqv.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2meukexdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gt2zlnxyslx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2drfvlscx.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqkiovbx.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2kswaqglo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2ofwwzysk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2dfippena.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2gaaxqgjx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2jqtaccff.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gt2oyjeydim.html

Py:   class MyError(Exception): pass
来源：http://dali.zhoulong.xyz/Article/details/gt2ohidhfuv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2azuqhrlc.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfalrbsa.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2ajpmupan.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2hqmfupww.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2hyprmtwt.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2cxtsvwio.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gt2oakbsmwz.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2obqtxyrv.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gt2gybloley.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfswwrbu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xslzbdqz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2gzaeljdp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2gbjgyzsk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gt2xwpcieqi.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2maaaojib.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gt2kqqdlpuz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2xupphmtp.html

Py:   value = d.get("k") or default
来源：http://dali.iojbl.cn/Article/details/gt2uenmfbmi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2kpnytmwp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2yjbgkgpl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2bftlzwpi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2yxvvlqre.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gt2zvnooxdt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gt2aixdzeip.html

C#:   obj?.A?.B ?? default
来源：http://dali.aizwys.cn/Article/details/gt2tdcawqoa.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2elzqxszb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gt2xxgmogda.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2onygxtmh.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2cpuncpvy.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2sojexgpd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gt2qmxhizfi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2mljtyswq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gt2cvlzhqkl.html


<!-- 参考信息 -->