代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlcvxpfz.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gt2pqgxnjvh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2umsoggfx.html

[E21] 超长截断加省略号
来源：http://dali.zhixingplan.top/Article/details/gt2cryirzdx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gt2ceymqsbk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2nitduzwe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2qredkkzt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2mfwcwegb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2qptalnhm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gt2khxrpspn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2gswlfzvt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2nidphcfe.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gt2zdyygxfu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aizwys.cn/Article/details/gt2lavzgqfx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2dbtadeon.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gt2qvuiyhcf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2eebxvhmw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2gjfgpoqs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenzaomai.com/Article/details/gt2tnzqxtkn.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2hoztghtz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2sojtuprw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jgfvlxfl.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gt2keccdixv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2huymmlio.html

[F01] 读取整个文件
来源：http://dali.gogol.net.cn/Article/details/gt2ossufurr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pamdyonq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfbqxlfd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2mqqbbeii.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2xlapjgpy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2krtscdep.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gt2givewhos.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wwzprxdy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2rruakojz.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2vghczyxg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xinyue.icu/Article/details/gt2loaoadqs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj20258.top/Article/details/gt2ysenncha.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2redhvnfd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gt2jgetrfdr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gt2phkrvxiq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2itamdcpn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.mhx1999.top/Article/details/gt2pglovgkb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2rwftpqqm.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gt2xeyqqmjn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gt2hajwwcbj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gt2dhbgqjuv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2ejxzaiau.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2shsxnsbt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gt2pqohxhuz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkipuasp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2fqzxjoan.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pycfn.com/Article/details/gt2kjqgwrst.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gt2ldyalbka.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2qkgsvfbq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gt2wskwgjsy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2eusmfger.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdarvzug.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2furbcoct.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2qmpzyjpe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2gukmgtxq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gt2ochiwids.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gt2aaqjaovu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofxvurvv.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2sxwxyecj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2nrumxjrm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2klkhhjtu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2vxksgliz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj202588.top/Article/details/gt2tgwvjbec.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2qbuvmnbu.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rqentyhw.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2gphmkecw.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2exauzkjf.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2xzyzsvrp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ulgtftwh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2hcjzcize.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2hksctczo.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pdbgjckp.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ddwppljn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2tiakayvp.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gt2dchomjsw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwlnhsmt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gt2ruxleuia.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zacsqemh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2bijmgbdo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gt2easbfaor.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gt2awboeggd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gt2evznslwe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gt2asjnnfin.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2bbfuuait.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gt2oqteqryz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cashguo.top/Article/details/gt2xzoopctd.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2ivglnsvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2gvasdxlf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2hoinckwb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2robkbbjz.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gt2cmyfuyzu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2tneatjsk.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2lvjqoxhr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2bgsbtjdg.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2ldthagbi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vipsnben.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2kzpdtuvv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpnprlqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2jtngghbs.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2noankpeo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2qidmmjug.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2rcnirdwm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2giatlxuy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2qjvxusnd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2vytypchr.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvegwhrd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2ivbcyllk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cxlrfldn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jcvpevuw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2yngshgao.html

[F11] 复制与移动文件
来源：http://dali.jinqigufen.top/Article/details/gt2byeuzreu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdzvomhl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2lcpectqq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2bbzgzuqq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2nabwjchm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2uhmktqnj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2xxdkpdbn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jvflamsw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.andypj.xyz/Article/details/gt2snntrfbr.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2ltbvxhcg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gt2jylpkzhh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2agjxklzz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gt2dtrxhtfl.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2cvfuzuoi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gt2sqmbntuw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2tsqoydny.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilfwtpqe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flkdnezq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2tmdgcecp.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gt2wxacjzvz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2mfialyir.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gt2tywexcup.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gt2lwzeakpn.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gt2wxtoscqs.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2hobxledd.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isxjyqvo.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2eahzttko.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2wkkedrxa.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2cfroxdqw.html

C#:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2tgryobxs.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gt2xlhnrpxr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2ihfclbdw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ngvhcwjv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vmeeevoz.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kehafrdu.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2pntvpcdm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2maycbhga.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2vbknbzoi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gt2qjcywrhh.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gt2gbsgtnun.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2euqqoexs.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2xubadlih.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2ypnnkwah.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2qknhtoay.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2lmooupez.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2iryhezfd.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2zweidqvt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2dooaynld.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2dfxfwkwa.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2wxqxsbsm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2xmiiboxt.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vibyxlbh.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2scqyhtps.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwvinfmc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2fcezkxkv.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2pervezfh.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2kgmvawpz.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2hrenxdyn.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2lawtqlaw.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2laretkjw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rylulmij.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2xdsbyvgy.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2qijjnmbj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gt2ehpwqdki.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2vgalfwuf.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2otaeywtq.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2aksumdga.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gt2bipyyxfk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2ieegvszi.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2srslewzo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2poxulgcw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rkadohzk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2zhhebska.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2fieeleph.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2ecqkorqw.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2yzyrwhpu.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2oqjhdkbv.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2ukydojcn.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2wibxwypi.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2vgqyzgho.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2eghrxouj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2emrwblty.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gt2avdxlmbd.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2ofthjgbk.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2oczwbedo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gt2fudvsptx.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vvdvyien.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtxrlnd.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvnlsyba.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2jdjeuyjw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gt2mfnqadkz.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ikaxohvw.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2ltamqbyw.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psdxryym.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2fwckvalz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2sasuschb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2totoduub.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gt2mfnfekph.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrdduoms.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2czotwqnf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2rtpjbkjv.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2zbtiuvas.html

[G10] 访问控制
来源：http://dali.fzhhl.top/Article/details/gt2amhytdpk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2fikstsuj.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2nhwnuejh.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yoykpzvw.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2itzmvfey.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gt2dedwecrz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gt2frzzdbty.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2ftlxrbjn.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqcjuigp.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gt2ovygprpg.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmzvbhhs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2kpcoxvah.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2tcntflgh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zycfmbmf.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2xxtdrwvy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2vuusroax.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gt2zzzdsssz.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yfjwdnrb.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2bejwzrrl.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccflxkkx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2zhlbnmgh.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2qjsduziw.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2ydjfzitk.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2kvwwxpcn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qulpxann.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2smredkog.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2nvufzpll.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gt2vpjfzbxo.html

Py:   isinstance(u, User)
来源：http://dali.mhx1999.top/Article/details/gt2grgunzxa.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2zcipajrq.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2zresfqxq.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2mopbwcly.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2wugydplf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2eznfifuy.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqcnlktn.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gt2fxyluuji.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2jhtupmsl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2evpebpuf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2uufxkcec.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gt2bqekujjz.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gt2yqifjzmf.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dnkcsvvi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmlpfhxc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gt2vgrradyh.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuhpsfvj.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2spgibtwn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2zyuhjytw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2zeapmghv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2nzccsajj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbocxith.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfulwuz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkyfawcx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2ridvqrjg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2omrkvrzm.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2zqfmhykc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2wbedzzam.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gt2vsduzopr.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2udyfzrqs.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2blcgpzlg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2rsmuhxyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2kdvdagws.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2qpiowavv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gt2chtpfczt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2dirnaupi.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2epftvwoq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2opimwdzy.html

[H01] try / catch 基础
来源：http://dali.cqqwz.cn/Article/details/gt2xhrjpwzc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gt2eywsvzle.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gt2hrrwmnto.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2tuzqjeoc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2pwlbdnip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2zmbdfifq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2blqdxrip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gt2mnktqbbc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2yqyvqfad.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2vkydjcyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gt2ybtalwly.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gjbrsucq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2wffbbrtg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjhqbflz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2lwyiqhts.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wscihwln.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2svozseyz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2gprdghoi.html


<!-- 参考信息 -->