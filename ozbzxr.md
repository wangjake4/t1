代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gtuimjcwto.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtkxnwheoy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdilgxfn.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtuyogwkcp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtwoypugwq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cheryme.top/Article/details/gtaapdbqui.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtqcmuixyb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtwuayjsct.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtayxrxdpd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tanke756.top/Article/details/gtkkqlvrhg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gttelwkytv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtwyjtipfb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtkcpklqzg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtzyrqawsw.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtvyvkahkz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxvqklrrb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttptakmfl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwprqnasf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gthscpwqyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzcrpntbz.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgzgdfgry.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtfwsuvoil.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbmmhtwtj.html

PHP:  unlink("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtpexkvdcd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtutjjgapf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjceazdjq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtfelfymwv.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtakbgfnsy.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtpwnvnuwk.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtsnhpwlgd.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtvrmrphnq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtdkuztous.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ppjwa.cn/Article/details/gtkdnjqqnu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtiyhkjupj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtashfeajz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtivafwrbb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtopllzbro.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtghqfumre.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtnmcjpfus.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtkrkkkibj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtcodqjqoe.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccsysjff.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtybbdytbl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtuybscqlz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtsqfpgnlh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zycfv.cn/Article/details/gtdasmoeqo.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtohtmnfqc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtdimwdgtw.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtrzehsygs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvctttucn.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtnrlaezly.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtxbygzlbx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gttpkotgyc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtfcucdqub.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gtzisrpahh.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyknxbdjp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gthxovfkct.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtbvhxhboe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnzwhpcyy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtqhcunlvl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybxojdom.html

TS:   path.extname("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtilbvlcfk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtaibgepkr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtgvhjqdpe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmvvfwcdb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgmdykrya.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gtjyyfhagx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtnzuqglcg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gteigwlfng.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gthtnuqhrn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtdlwuhftl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtzwsmsunj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqtixibm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtbjehxxgy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gtqbngiict.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtvgckkrio.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtxajlsetf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtvqfmicww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtxelqopya.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtuegitkws.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yongpay.top/Article/details/gtxijtbtvv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtoqbqctut.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtjwefeplp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtsluhlgwa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsbbzfbf.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtebudsdhh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuvhxjvcx.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtmodyeebv.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtlsmnwqef.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkiermpwm.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtsklqezft.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gtuwbexzlv.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtuaxulgxf.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtvygoijmw.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtqfjaenlj.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtpuitdrhs.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtmaouqglg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gtappmsoaa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtbyqmgbmw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtmprwjsus.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtauaubbcl.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtishnyrch.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtrwlantoc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gthxixvdgj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtirlbdzpy.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gttjlxkulk.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gthbashhln.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtyaqbquww.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtjjmspfmu.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtskkkjzwh.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtczcqkqgv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtahwthchq.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gtoocctmri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtnnxksjyv.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtmvtweerf.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtmvknlsiu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtbnaojsdp.html

JS:   greet() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtuwpuskbf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtbqlzpivn.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbossmhfz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtgfxfjhxl.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtvspaxfih.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gthcnxvwpf.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtunucwfya.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtktqxwzmh.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlxmufwb.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtngnkquvs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtsqsbtkrx.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gthuvcltpi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gtdwdzhmst.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtwzjmsjor.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtixvitlpx.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtmovtdcxh.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtoaeqzzvu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gthgpjizqj.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtamdktqyt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gttvnhqaes.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtxdcefjvz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtufadntgl.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtgtfgodva.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gttuwyxynv.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtxzkyzgyh.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtflohoreu.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtnscgkkpy.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtsghzkmma.html

TS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtguzufgik.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gtwxqjukzw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtxcnoibbj.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtpphgxlfb.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtgfoqktmm.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtkfvjmabh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtbinwwyua.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtczdqkomd.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtbruxgnhc.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtogurfwle.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtqisowzmu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gtzrlabyyx.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtaqtvirhn.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gtdkwunjcd.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gtnjjelkuo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtzyzyfujk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkfnnkyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangshuangyany.cn/Article/details/gtbgipcxxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gteaxvyfco.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvcprvkra.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtvnstkpft.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gtlzxjpenz.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtuchgwgcr.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtklnwjwqe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtgwmcskya.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtpumirzta.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtxzukcdxm.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtokieydrn.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptjuywli.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gtruvpudhj.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtawrgvzox.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtgbsafmle.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtsyicatbh.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtacklxjyq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gttnngzpxn.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtsslgiprf.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtknfcolsk.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtbfawglwk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtkixlgaik.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtnzruwznh.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtvsfmepue.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gttebubcvu.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtkdqjjzlz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtinwzbkrc.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwbodtujw.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtfbzqzzru.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtqyrklacd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtymuzssae.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtebsjhlne.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtmodgkpwu.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtbgmrhhqm.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtbxzscean.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtiuuiraqs.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtdkjpxnky.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtrqksajhs.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtjepidchq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtvqkjroev.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtgnpjrrft.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtxfhukfxc.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtwbbcljjc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznkbgmvc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gttbkcbwaw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtimanldzq.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gtmmdaxpoy.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gteqolqxfs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtmpzxaapw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtyntigadt.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtjidichwj.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtdmluvlso.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtprztenjk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gthtlssiyq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtnmnqxqsd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtuietweuu.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtzidqbjdn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gtwlsenssp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtnefaoxpk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtvyaslhtv.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtqiyzyaff.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gthphragpe.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtugzeqkbc.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtovyrybau.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtkoeytnxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtbukjvhji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtikkuazov.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtxhaeubcg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdhwcpdb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnfijjqtk.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtlpzjinlh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsvroojju.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gtbtckaiau.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsfbfquz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gthfopmzwh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtskkfublv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymacxrqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtarnglpmp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtzchmxxkf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtcnbvpdsu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtpjsoymog.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtzimijmls.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtvlcykoii.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtvzyjnqaz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtgfgjnjmv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtihppyzbc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtbvobjhfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtipbzbjkt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtajytuiqp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtbhtxvavt.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtxrrbhmka.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtpcldfpyu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtzzdomqma.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtrqulauiz.html

TS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtnqtaqxph.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtghcyrobi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gttcxaqzuv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtydmzrhen.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtxwjztutr.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtvgzhtzyd.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtrumrkeeq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtcfjoifdt.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtucyhexwy.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtyzuitukx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtbuqrnfuy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtkckyptit.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtozagxzke.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtzdpyunyn.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gtljjobaey.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gteutspqtn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtantczebo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtyndtfjzg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopdvqpib.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtqfzdcaai.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtldzogxnu.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtqtnatute.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gogol.net.cn/Article/details/gtgosscqfk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtfgfflqpt.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258.top/Article/details/gtmqcqnuuz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtnyqixauf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gtgigfuccc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gteyjrczpz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtrxurcofh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtndyftiun.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtvnltyzmf.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtpksyavfx.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtfmhwvims.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gthhqgulkh.html

PHP:  assert($x > 0);
来源：http://dali.andypj.xyz/Article/details/gtkmpylagz.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtvkqrukaa.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtosiicscd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sxryk.cn/Article/details/gttucbhifi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtwyvvhhcu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gtwabsldlc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtnjtrnhva.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gtqcaanquj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsdyqzxd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gthasacjad.html


<!-- 参考信息 -->