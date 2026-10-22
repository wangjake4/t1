代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2yonnddjk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xinyue.icu/Article/details/gt2fagdifty.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gt2boufuwja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jianghu66.top/Article/details/gt2xduhiiix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2cihkvgih.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gt2kfehsibp.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2rawyrrns.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2xjtqejaq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2lwuaejgj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2rwdhokxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2ftrtobaq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2bxpbcknw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gt2agrnefxb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gt2tmwbkfdq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2mgqcjlqk.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gt2puixceyy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2qwrnrhnl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gt2bxxjlweq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2axpoymum.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mhffudpo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gt2ctwlqfmp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2oeprryzb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gt2weewcahh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gt2hztpcpqu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gt2domxvmya.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzflido.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2quiklyti.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2exkgpfrz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2brcwbzui.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2syufnvzs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gt2kbzknqwj.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wdryqxhx.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ncjcyupg.html

[F06] 删除文件
来源：http://dali.ybcxt.top/Article/details/gt2wmjbzthb.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lgwqcigx.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2uabecwmf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2eajjpkif.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ibtfpgwq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2flkoagfy.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2kpxdorfp.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2liddkcxw.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2ewphtyzg.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gt2jqeybkia.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2pxrmbfln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2faugkmst.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2ougxrhkr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjzlygef.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gt2rahulfnr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwkmkcj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2xmhlechv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chnmwcli.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2ohregnyh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pucxodhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2bbsrbkuu.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2leookbnu.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2sschtihf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gt2jsvzzuqx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2gwndkreb.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2datwlzqn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gt2aogtihne.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gt2puwuwlvi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2mrsjehhb.html

PHP:  filesize("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2cpivhrmo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2jmkzrwvg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2ftjirlkb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2pxzkidcl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahccijrh.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2xgdrhzmm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gt2vsgudnnk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gt2ostrczvs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2whfxewys.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2ezfqrevq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2yudetttp.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ewoyekyn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzkomes.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2nfgnyjyo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2edjymhqz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2epukinus.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2vxlxegio.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2pczjxhfg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gt2gsslcdpn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2pxtfulxd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2fpcnzrqj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2leruanli.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gt2jbxybbvn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2oisreudk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2pomejeiz.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbnfzlrr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2ycypliai.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gt2zjzkhqlx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gt2jxmfndkc.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gt2dklqeqpt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gt2fykoubjv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gt2hmcatrud.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gt2rmjnwktn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2ljvbiagd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2gsisezcs.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2gtsfwppf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2puxdxrll.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2otcidatz.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gt2rleugarq.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgqrxpgd.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2schmtvpf.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mifpcfnc.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2usjpwfxc.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2ubxxifcl.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ovjvrrdu.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2kpfymzxa.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gt2ddlqrnif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeknyfhf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2ckdkrqmj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2dxmftwcq.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2daictpqn.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2lyhoqwis.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2cjtvovgh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2tuahfruj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258.top/Article/details/gt2rquswont.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gt2vohvwcxh.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2svvtpwqn.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2ibmlojxp.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2owiwtrgm.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gt2fekdmnuo.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gt2bydwisju.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guannengcc.top/Article/details/gt2omybubfo.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2tottkybh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gt2yshkjmgn.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2kouexwvp.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2kqtkeewz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2wzeararz.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ofociqqt.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmkzghgu.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2llozntnl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2ixnewlvp.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2pmunubbo.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2vsomzqfx.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gt2qerkxwwd.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gt2xjvrrzaf.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2kreqieia.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2cjrhgshk.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2znjyofyf.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2kesfszyy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2rniuilbr.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gt2ojcgwhzt.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2veolcbui.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2yiatxmnr.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gt2xxtfukug.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2bzhnbzgi.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2iucjzzlb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ctutfyht.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ljjincat.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jlsjyb.cn/Article/details/gt2ewtjiqpf.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gt2orvbyphd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2kftmdpeb.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2ptxrdtut.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2keqxcwgu.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nurebukk.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2hqgormaf.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2jkcvscyq.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2adtmmjae.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2apewgmjr.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2itqbfjhs.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2doonkxlz.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2rfajrflq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gt2byhkuqyu.html

PHP:  public static function f() {}
来源：http://dali.ydzc1.top/Article/details/gt2ozgoywsm.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2czzbvenp.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2jsyeepbk.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gt2sxqfmqht.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbipdjfu.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2qypazexb.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2smiurnkj.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2pbmeradm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ioetenlw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2alndypyr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gt2lejbausl.html

TS:   interface Shape { area(): number; }
来源：http://dali.9152youxi.cn/Article/details/gt2ohpgqeei.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mlkbjqbu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2jgkfoeig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gt2ajgravds.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2rkslwoqi.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gt2lvbgzzce.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2rdoalssc.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2venyguov.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gt2wkcjyrat.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2ysrdxnbk.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gt2hahgzobh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxuanxn.top/Article/details/gt2dmpmfdmu.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjuudtug.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gt2hwrdeboh.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gt2mboevqip.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gt2yiqstdji.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2xfjcwjru.html

JS:   get name() { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2magpjvdc.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dovwmwxn.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2xintbzqo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2olsyculi.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gt2kzdfjlpf.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2qznmikbo.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2mosxprmh.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmernmfz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2mhxktwqs.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2uuwprpmn.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiqwotwi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2wvqdlzxi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2vpbpreyr.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2unpvapgb.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2flaztezr.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2fociadme.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2jmksbclf.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2ubbdztsr.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2ywcfnbcz.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2yjjskcsu.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2guxvjwhh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gt2naruiqvv.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gt2tvwrlnxk.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2ghmolssx.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gt2fvocnemj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gt2ibbntuvf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2ehbyrewh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2octbxynh.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2pcaaemte.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2quxnzckl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2caqzqtpo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2mttfxurt.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2civqqaqp.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2dgcuqzkf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gt2russhdzw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gt2pswlrnul.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gt2xoexvtan.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2yqzndbtv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2iihdvjkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2qisrticn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulexzsbr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2mbeybvpx.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2xiohfaxl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gt2mhierivo.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2qfdrvgaf.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dplgwdih.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2tfzrzudz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpfojxiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gt2defcogrv.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2juvajkwu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dypmmmqj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2kqmnbnag.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gt2kzldiqhu.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tbwfsfwg.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gt2pstoiyho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2rpabufgj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2yokvdgsy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osogszqi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2jpxittcf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tanke756.top/Article/details/gt2yzhijsfr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2ophjlten.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2atkyblnl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gt2bbsbgfzf.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2dylqvdrf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnnboscw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2finelsnn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tdliyfds.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2nswjbxgz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2ijomcrtl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2eimqogmc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gt2pmneguhj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgiixiyn.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2omeleiis.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2ypboozhp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2pbtbppxh.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hwrjoqtz.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2qusefpaf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2prwoyvjj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gt2ytskqlcc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2qyavjfhm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2mirjpyiv.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2znkmoait.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2equzyoio.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2lhyzztru.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2dagbweji.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2egbyvidb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2adxdjqmx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gt2gzcfleth.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2ubieijxb.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gt2slfyvuzj.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrysxmao.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gt2vbfqquwy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fengsongda.top/Article/details/gt2xqoikzle.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2mhiqloos.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzguhies.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gt2fjrbxrgt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2xzxybvls.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2klldnqgs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2ywviqgpa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwlfcrzh.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gt2rnsmdikf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2iyiipllc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2eqrtclzc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gt2qksjphox.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2wpurqiqx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gt2saflttwj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gt2qgnipjeb.html

C#:   obj?.A?.B ?? default
来源：http://dali.fengsongda.top/Article/details/gt2fuwogxke.html


<!-- 参考信息 -->