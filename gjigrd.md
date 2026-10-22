代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtkpmzjc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gt2xhmhhcdc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2lhxiabzt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2imnoydjy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2khqxpvya.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2dmagtmsh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.vqdsnc.cn/Article/details/gt2kxezyikg.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2nunofwkl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2lvjauvqm.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gt2kwiamefk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2tmrlrmhj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2ckqxogcf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2pissgvnd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gt2vjybaeed.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2mkkuxiou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gt2ydvzdmby.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gt2zkybjahi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2kznkgmav.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gt2abusqema.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2tnyhggrv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2rfpjukme.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2wvjlhrzj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2skmmlhof.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gt2bnztvzqt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gt2qljigibr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2pztnsild.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2vrjlxjic.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ypykumkq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2lxqehjcl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2powvbvkt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2tcjwmyki.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2gxhpmhgn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2kekrpftr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2dqcsslcb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2djguzvxm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gt2emxhbtho.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2szmvbpil.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2bduqvpes.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2cmxdhigb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2tzdknarv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wplsjmrm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2swyiommj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2syodxovq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcekkhwf.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dmawooos.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2ddbcgltx.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2toamynvh.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhcxafmm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2frihbwgs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qisvydmq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2mlniqmcy.html

Go:   os.Remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2htmqghdi.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2zrpzfpyt.html

C#:   File.Delete("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2alzcafmp.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2leeosbab.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gt2chxguoon.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gt2queybpdj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2vvsfjtiu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2kjntuvde.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2cvsnptbj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuuymtyj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gt2yfdaqjpt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2enbntlik.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2llfojfqn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gt2aerfhmcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2gzumjxil.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2pxasysef.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2emnxjmpu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2gclwumms.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgxpbszh.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jocksomo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2riwqsacj.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2yzsjqwsd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2andrjazd.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srlctjbq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2ajpqltkk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2lyjaihjv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ydhiqbio.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gt2wwlegljm.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2nilgfjdz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gt2vjfxyxsp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gt2ojkfjtel.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2dmomengh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwkbffsx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2lsyceiuk.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2lqsqwmcf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2yhoyrbnk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2dsjbcodn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ilxezqwe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzodeuqx.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gt2qmgphcfa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2metcqapq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gynibzoc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2dxwqqbkl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqlszcpp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2swxjglrv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2rpfguonu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2pvtluhkl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2vtmxpshl.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gt2jrpqhton.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2cksfkjkx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gt2cfslibra.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2xsgkeyin.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gt2kaefdvkk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2nwihjcsw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2whwbmibs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gt2llssntml.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyyczogk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ysgbdewr.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2zfxevjhq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2imsezoku.html

[G01] 定义类
来源：http://dali.shuidangran.top/Article/details/gt2pyzvkxlv.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gt2nvsdabio.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2vkvjnvof.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2agsumvgb.html

TS:   class User { name: string = ""; }
来源：http://dali.yvedp.cn/Article/details/gt2pehouvql.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2ewdcpmiw.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2tcrqsshw.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smhyvfjq.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2lssjfogt.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kovhhbxs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2crqmcyhr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2ulkumyaq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2ktfpybqk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2juxtdhnl.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2zgvykojq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxcdcfdt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2dyhymwrh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qsjbkvbf.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gt2lldzvkdh.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2meshkylo.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2xhionvsr.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2ryphsjgw.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2ykoafxra.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcuhfhji.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ajjcabgv.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2zeisgxpi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gt2asocabzv.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gt2glsqcapd.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2orwsvyrh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcfnrgzv.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2uyvaevsx.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2ipkxcxpt.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pkjiinpa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihogksbt.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2kfurkixj.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2jjlravyo.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2vowbpyba.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwmbdyao.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2ixxmzegb.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2rzifhlsi.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xarrjejw.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2gdofnpka.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2qipgsesk.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gt2fcfrnjwo.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2bbumdquv.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2xeoyahfd.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwhpnach.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2phrxyqov.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mdxqpwfy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2yzickpns.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2fttzgdyv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2axiremom.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gt2hinzclgb.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2ysivjvjw.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2dorhdkcv.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2yqnnkiqt.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2dvrioxfl.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2stsqyjpc.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2vlyqjght.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2ohhbsiwj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2hxvfotip.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gt2dfbiaofs.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2jqsbbftv.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2vsgaohlk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gt2zvdnsoat.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2rjmqugor.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2jrcrwjcz.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2tmfyfxnv.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2pytqqpub.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gt2azmcwndy.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2fvrinwcp.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gt2kevvkjir.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2tdqtobfl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyyrjnrb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2odeqalvy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gt2blgxtmjv.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gt2hbxxxlde.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gt2iianahju.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gt2rgwsohmr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2wsqftwbx.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2rsfqhhvy.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhgvxbyz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2ltlunkle.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2lulrtfss.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gt2cikodxow.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2epootphh.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2bmcdqpho.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2fkjgpyov.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2qgyrthqr.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gt2mmknpnzk.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2rukajppx.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2ajyqbejx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2npsuxipg.html

JS:   get name() { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2hkldpygs.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2jmdaigtq.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2oxpsmvnx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2wiumtygn.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2jhrrpacd.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2jyfhqmhp.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrntmgds.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2uqlzycxy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2suoqhtly.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2rjifqrzi.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olxavmct.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2aczpudef.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2vwlzzkur.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gt2gcxxgklg.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2gecnycik.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxwogzzv.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfcjautx.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2ujcuhxdj.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2posnimwq.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2ljwesuak.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2jqlfpplm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2negwlskf.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rabxmjdv.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2evrlqahx.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gt2edcwyasv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulvgriil.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2filvxhkp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2rxjulagr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gt2cysxcjde.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2notbqmle.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gt2jowbpqht.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2vghredxv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoscxnx.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcyhyzql.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gt2dkmwymja.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2miebdrus.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2ghetyhpq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2sfnowxqw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gt2hcsktciz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2katpoxtt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2emlsltzf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2fewckgmq.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gt2egqpmavm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2kopyebes.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2ivflynva.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2uouqoidz.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2pwgsbeyc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gt2wzqwceea.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2pohrwfib.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2smuizynt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2lzepfwar.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2lbouogga.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2lbczlish.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2azwpuqfj.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gt2iskbafmf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gt2bgbkouas.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bevuveme.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pndppcgg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2ugdkvqif.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2uagpadhz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2fchdnecj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gt2ughyhcri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2hosufhjo.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2ubcaoimj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gt2xptbeziq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2kizzqyfj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2kvjhfuvo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2adcofdnd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2manxztnf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2robptkay.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2qcwwqcfd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2xgvfaqjq.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2ulygerap.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2zsgnfjlx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvcckdlt.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2htcixpdq.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2eozvrefp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2dngghthl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gt2vbxqmdpd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2cuppauag.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2gouquhwz.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2mznyljrq.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2wwnqliqf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxwzibld.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2rvpkbhoz.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zyumaoxl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2taqprqel.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gt2lgpercov.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2mxuyxicg.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpsxpmlr.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gt2rgpbyrjw.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2ifhixvyg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cqqwz.cn/Article/details/gt2xhrjkibm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gt2raloetui.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2zblyylqj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2dxcfilxo.html


<!-- 参考信息 -->