代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gt2dvqatjsb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gt2kweavicj.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gt2jmutnxto.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2babshpcz.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gt2ddejvfml.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gt2jxryafqg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2jfjcktjr.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gt2cinvjban.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gt2cpohloky.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2fdvduxut.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2dykxvwyw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2vbrmqwmi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2xgmnyfxf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gt2xyebavjd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2kwsdhbsf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yutyxunv.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2wqzpxyaf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.9152youxi.cn/Article/details/gt2bididqom.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2icojtjqg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gt2iierrxte.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhssidor.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2kpykrnpl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2tyvzhinz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euvaodro.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2wwfhahty.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfzmuxnx.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gt2utrfhaeo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2qnmovycj.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gt2nbhnvgfm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gt2jmqzcufs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2lofcitax.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqbfqxg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjqbnogl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwtpmajk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gt2crnxwiip.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2fkegourr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2xgneyqxx.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gt2phpdfotx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2cvluuiyq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztggqlcm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2inewrnxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gt2vrymcges.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2lwkaicoa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gt2pchaugch.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2kkcpqevz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2svltssil.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2udsbvjca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2znoxqubt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gt2saptlwhm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2xpmcqgsp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2gdxhtiam.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2crfmgzxr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gt2rrtfemcl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajutcpks.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2zigugdtf.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gt2mnkhaalf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2svnirqkd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gt2jpvrumpc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2pcugbubd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2atxegzmh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2hvlxdxii.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2jugpplwe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fzhhl.top/Article/details/gt2pwrdhoko.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gt2pjbphyat.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2dhushqbj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjfmwigq.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2dffqudqe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2yguyzwdx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2codyvmrr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2vkvjinor.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzfhnjcr.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2nkrxqeav.html

C#:   File.Exists("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2uhwpmehv.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gt2kajeanwx.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2mszymgvp.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2ptgzgykm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2hyuuabms.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2cgishdsa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2abctkksz.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2prqdpyco.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xeznuoah.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2einifvxt.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gt2npbpmpdk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.havefunace.top/Article/details/gt2wedjxbdj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gt2bbqtebqt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2nxmtnxha.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2qitrwqnk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2ukvzlopc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2xccobbgu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sysykeji.top/Article/details/gt2hdwrvfxm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2vwpxtnbh.html

[F08] 遍历目录
来源：http://dali.yuxming.cn/Article/details/gt2akllhkrw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2yqysvbri.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gt2fjawyrhq.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2zfmcsqua.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2oyunshyo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2ftopdrwl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2whuscdsd.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gt2fkiiydzs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gt2uiqypnlj.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2ijargpfw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2kobgpyzf.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2bchlnwbg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2rviuzpqh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ginsfrym.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2khaowkhr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2kryfcunq.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2corbzygb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvuozsay.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.c1oappe.top/Article/details/gt2hutdwpxx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qeskejzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2wncfbaqe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hyaomvhd.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2gagjmlqb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2vmrjlypl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ptysktpv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pamjhamg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2firmtwje.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2kuashijm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2towzegvx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2qkrfjhlr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2nwdgftvq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2sjkssxrw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2lgoplqni.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfbappwf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2jiqkknoo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2xxpggmek.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gt2aowsieue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2tbgvkvkf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gt2hopmlcvq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gt2zgzpcsob.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2dogdlbwm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2xdqatcir.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2ofmecpop.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gt2sxtqclom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gt2sjfjrpgd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2tulmjfrs.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztggdore.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqvnabbq.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2bvxnwhsd.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2ynyqksli.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2nkcbsajp.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2wvjnzlbv.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gt2authhkem.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2wxxqzazq.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gt2lqyjhrnc.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gt2pvbktiwr.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkhwmgfa.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2quvjrkrs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2xsazwjco.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2rawtatzh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2fkukcrsf.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ufizkupg.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjrnchbs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2opwxtisx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2obpacqhk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2bzqeaalt.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2idewkjrh.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2rvkugtps.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2qbtshwjs.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgvztmjo.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gt2alhssfvk.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gt2cljmoadh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gt2pccmynxj.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2paypvhot.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2uxuaxgih.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfennpos.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2fpsejkvu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfarhihq.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2pobxbinu.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yyysslbu.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqxmgnpm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2drpcfewc.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gt2tecjckqs.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2xdeknkqp.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2maufifsn.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2ywjtulmy.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2bqceaqne.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2veshvwij.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2qsdpiuul.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2xxjtodce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2bllnhzud.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2pqzdwyyf.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tbxlyfts.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gt2jivvwfzn.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2smbphqte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2sozodtmv.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2kdquwxul.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2rfmvmzfq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2yjttsysy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2gsvrvqhq.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gt2iwzzaetw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2ljcycyuw.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjxykecx.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gt2cwjuviia.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gt2gcjuvjnq.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2blgizwvn.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvghsofw.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2yngftxyd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gt2yccqcepn.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2gcdsmloa.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2eadhshua.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gt2xufczvha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gt2ziqohger.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2kqtlhmcd.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2zfcrfkmr.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeuaedoa.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2agodbeyz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gt2tkhajile.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2nwkolrwo.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2smgfcfpc.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2qtuqfcvg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2emulkpon.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gt2kwdlytwv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2idhkzvbs.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gt2okvteytn.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2amagdorr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sxryk.cn/Article/details/gt2xbkkbffg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2sactmcyt.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2qmzdxndo.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2agdcjftw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqrytgei.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2mzvflxzm.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2yngnuzpk.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2bijgkjhx.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2rrxcfsqh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2vayeyiym.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2ciggnjiu.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2likemwtb.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2vgvgpfwg.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2tzfvhfnk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2vwujtrcv.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2flrwfpks.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gt2qjfxphon.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2pbllzhlz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjfznsfw.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gt2fomhgjsq.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2zjrpvlzj.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2mdponwwv.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2pjdtuyac.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vypgfxxd.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2wpevhxij.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2gcrdzlqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2zybsfyhe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2ccjvaenq.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2lnieugal.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2pfozbwct.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2pnqwlcbt.html

Py:   isinstance(u, User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tindyguz.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2bivjksgo.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxsaebpk.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2pxlxlcod.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2simsaoan.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvvugbyo.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2poqkroik.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gt2cxzsearj.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gt2fcuvernk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2adzmlcjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2uwsyoxyr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gt2dyemstly.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gt2rkfcdhcq.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gt2mvznbgkh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2tuuzlevn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gt2gixqwmlv.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gt2kppekqdu.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2gvgpzmqv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gt2ptctvajy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xepiymas.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2sefvadkz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2zbwyngaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2dlzapspt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gt2btsryekn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gt2gocsqdvd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2vdnkfexy.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2zsdayagj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gt2dihtkagt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpajdsy.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2ozomkeqx.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2cilfknpb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqimogud.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxutjqka.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzqgfwhb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2rysmppnu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2sjywxxjt.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzhuoprf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2abofvjyo.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gt2jhrlybnf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2kkmyyyak.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2fgiqqkyo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2bbhjsvnp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2frgrxspl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2ksrdtitb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2iwyzmjsu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2xfqqqxpl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2rugeialj.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2lpnbngxo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmvklqvo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2hafviwok.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2jbxkxulu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2iowrmvxs.html


<!-- 参考信息 -->