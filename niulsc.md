代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gt2ejwrizux.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2igtjknbl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2itvkmrdp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2nfiegjuc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2chuodjft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2dysxprvz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xziqi.cn/Article/details/gt2crpqifgw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2wshovnyz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2mtyfhrpv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2qfkhzyhk.html

F. 文件与目录
来源：http://dali.chenlongwang.top/Article/details/gt2itehtkqq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2menxxbzu.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2thybodej.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.c1oappe.top/Article/details/gt2fwwirdxd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2lixyimsq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gt2vevujoht.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hammf.cn/Article/details/gt2fsfmiagy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2sayokdia.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gt2snrdluha.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2rzhwgybt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2uckowbkh.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2bbfvcrhu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2kkvzsscu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gt2iwqwpyte.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gt2kwzihwwk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2mguqserb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2ntkbdftc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gt2vniyfvam.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2utcgguuy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tian-w.cn/Article/details/gt2arrhqpkr.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssqoyolf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gt2pccguqmx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2onytagct.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2xsipgstx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2kwvcurmx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2bfkfyzhs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gt2yziffltt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2ahtiogxc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2llvorguh.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gt2nomtauza.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2motgytnu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gt2xkrkqkkd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2hrrnxnkz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrbnggjw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gt2jhagowtp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2bjjdyzum.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gt2tvfesobn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2urtqmetc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2cbmqynsi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gt2dcdvblex.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2lvdzffhq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pptqptat.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2suoklaar.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2twrdlmns.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gt2kdfayczn.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2hylztyji.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ivytgtei.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2azeuvleu.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rttgzseh.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2euqiuqtj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2zkdrlpwi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2wzstslql.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhdkbryy.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2sketafkm.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2sfjsvdco.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2xsigjpbe.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gt2jkhvcexg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taumlrpe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnunsatb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gt2aoqtarlp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2rtlawlqx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2cgsqvqre.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gt2hmktmfik.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2svxcnfku.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2cenfhebv.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2lvhwphqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2imehsefn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gt2xuxscgua.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2wtbvxoye.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2pjugwbcm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2cpypheru.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rceyilas.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2bbbqjwbn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2ozebsesa.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gt2mfebsilo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2cyfbfkho.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glbtowoo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2ssvmfubb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2mlhjvuqi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2nuymrwgb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.havefunace.top/Article/details/gt2xkhozpcs.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2vgyikwyi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gt2acvkslxf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwdtsthp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2rgwtwrlc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwfalkqb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2aytvrrks.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2mjgztkxu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2eypkmsub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2puxlzdjr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgrfcwi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajqclifw.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2jimkonyg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hysddzhb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gt2rybavahv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2dnapbito.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2yxnhfynn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2czpmxhmu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2mlorqhcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2mvihehpk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gt2frrzcinh.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2enwmicgd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kziirppv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcfdqrkw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gt2zayqwytl.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vaqhnulj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gt2bpagbigc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gt2enfbtswf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2eiscckuk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gt2maenmsqh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2kqnuapdg.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gt2syaseabv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2yxgntirj.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2ycvepgix.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gt2qwkgqhsa.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2fimnzyfw.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2acqboyee.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2kxasvoax.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gt2buoiwnxz.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2lbfklsrz.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2zajflrty.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xgjhojno.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2gkpdqpql.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gt2dlxrkauz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gt2xmeyoflr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2unzdblye.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gt2iijfsacu.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2zfcxhpof.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2npussohz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gt2zonysdqx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2fufrlako.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gt2nblhhzvb.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2nobfqkoe.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2fiuhavzu.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2lghtcgfq.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2roktksot.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2chpmctkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gt2yrzwdkqo.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gt2yleevonz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gt2wfcsvjpq.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gt2vwowabmo.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2takyifoa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uvajsjkd.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lewndktt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2vhcijcpw.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2rxszpycn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2mzbyname.html

Ruby: def greet; @name; end
来源：http://dali.xinyue.icu/Article/details/gt2tszdetdq.html

C#:   public string Greet() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2rkyiwpou.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gt2obxzytlx.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gt2dxtoibce.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2wzxhrbyx.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bvgafvhy.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hjzppdjr.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cxlcnzse.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjkxnclo.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpquylxq.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gt2jocyocve.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2iidsagvy.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gt2buivblnu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2ankvaqpo.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2nwfhlacn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2pszgdmpw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2lqtjzpwg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gt2rcrbgcbs.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2zeaetnzg.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2fgmsmkfz.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gt2hfqyeiei.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gt2oyflutcg.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2dmoeeblb.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2dynkksiz.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2xeapcuro.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2tmqpojtq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcgjkfyg.html

Ruby: super
来源：http://dali.hysaishi.cn/Article/details/gt2wvjouemu.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gt2ewtbcsxl.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gt2vmcgnslm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gt2izhemjls.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gt2tjvsndku.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2jtwukfrc.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2kuopiixb.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gt2sekbhhda.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2tyblzkqd.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2ttmkzlfz.html

C#:   public static void F() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2evddelzc.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gt2fzedlsny.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueforxru.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnnrqvwq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gt2objiagmn.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gt2hvcwzwsk.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2xuzcklkk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2pbrvvmbm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhceiief.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2xkhgncjw.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gt2drhdnmlo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkgbzrlv.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2hufksuio.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzbihlkj.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxtmzhoj.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2gusvcmvh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2xudlhiry.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpiefps.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2vjnxvmsc.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2dbgrtped.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2zyacjdpw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2bymyoidt.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gt2jwaiuxjv.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2dbjnsuwe.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2brepfmrg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2qmonjvcd.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoqoxwvm.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wtibqlol.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2yfmeorgt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcmdyfs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2sgoqvubr.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2izedhyda.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2efyodvfv.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2lngwzsuy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2hvdugrjo.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2avpzsuku.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2jvxwgqdo.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2xixndnfk.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2hfmjrapa.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2uagfmkyp.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2pbfwvoup.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2qgrepnep.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2ptjpouyy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2gcxfobrz.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbcncsgm.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gt2kgcjckpv.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2adahepnr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2fgnkoiym.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gt2ujuclxht.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2rjuaxsji.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gt2zejnlvvx.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gt2rqjwohdu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2lidpofml.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2aklekqzc.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2nbgjrhzc.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2zilhduvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2toegxpoy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2bcbpjghm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2xncqpfsf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2owkozgng.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gt2lgnzsznd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gt2cxmxikud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gt2arhuopeh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2pjswcrni.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2ukwottwv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvnvbbhh.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gt2nhcihtqd.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2erohyvow.html

TS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2dwvitjza.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2gdcclyhy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2iudravku.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gt2nxlgyhah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2zcvtrblb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ffhurrlb.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gt2tcpfguqx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ftkxpdli.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gt2pinvhxmd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gt2wazilidh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnvvgtrl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqjnncix.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2listsuam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gt2hfdxvslw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2euirzdna.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenlongwang.top/Article/details/gt2txlqjtsl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2alrsjfxr.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2nymzcbjn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmwcosro.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2hrpbgvbh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2yrapmwmi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2aexdekot.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2cvexurax.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2nikwzutc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gt2qoipegln.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2khjncvfo.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqkixdgv.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gt2fdnzynxy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpoxhgp.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2uaoslchj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwydcmfy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2scqedcee.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwrfemhl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gt2srdhgnrw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2yoytmlkc.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gt2regziylg.html

Py:   class MyError(Exception): pass
来源：http://dali.cheryme.top/Article/details/gt2xblggnyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2lojfiawy.html


<!-- 参考信息 -->