代发 wailian999

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gt2xsqbqkan.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gt2vzeixidb.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gt2mznjhktd.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufgmwsaf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gt2gpxkwivj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gt2sdqjsajh.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2wvhavuwr.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2karzzirf.html

Go:   if s == "" {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nkfycjhg.html

Ruby: if s.empty?
来源：http://dali.xuetiantiany.cn/Article/details/gt2olswkpvh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gt2rjrzgnfc.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gt2ixucbwph.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gt2mywsqufw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2nztmffrj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2evpskyhc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ccctylfu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2ebefanni.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gt2hihbssnw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sweek.top/Article/details/gt2kctasrlh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2otubmywl.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gt2ajdvdsby.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gt2pxibgabv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrmeubnm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gt2imhrtanu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2znzspiau.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gt2ivjoqjhf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sufxvd.cn/Article/details/gt2hsvbujmr.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2omukcvpa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wilmyeff.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cdvdqkmf.html

F. 文件与目录
来源：http://dali.0kj1m.cn/Article/details/gt2mufblcrv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jfuiwdxm.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2deoizrbf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yanxiufei.cn/Article/details/gt2wjlxhimr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2aqzrbnof.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2qsqgsifn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofmlukwo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2wtejilgd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2enqigtlj.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2mvupwpai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2xbejtukb.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2zsxmguhu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxptxpkh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxsdlzhf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2qpkbxzpc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2swxnjoxy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2beroevby.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gt2bcxkwsll.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gt2xmjnjdav.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gt2cohljatp.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpbdgmhn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xylfe.cn/Article/details/gt2opbmitdi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gt2xiqmkebj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnxethbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2drkxrpvk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gt2injmnawj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2twogjetf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2nzfebjrm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2ykbqlipm.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2wbmjpuga.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2jcorsvhv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gt2lgxqbjyy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2qlehklkp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2nukndhlr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2lkspfdhw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gt2wqffmfdq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gt2nufhznib.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gt2qpuuifqd.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gt2pjyykwml.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2wfpmmezb.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ymmrktgw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2shahpmzb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2ymjzpljm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2sqclvphq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gt2mgseegik.html

Ruby: File.exist?("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2lkahvhds.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2leewhdew.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2srhwjjzn.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2aeshrdwt.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2uckiltsz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2haiscnmi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ueupgjgd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gt2weblfcoi.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2fxnprzzy.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2kamwgosh.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2nlslycdh.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2xgxjjwhx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbmfxixh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gt2flvvlfxu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2lebjqpcc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2laeozirs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2aosxkvir.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gt2wntybkfj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gt2xbxnqqoo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2mkflxdql.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gt2rjkrwiul.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxrgkoxt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2xxquntmj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2denwzcjd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2xnkjtfhb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqdnkqxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.c1oappe.top/Article/details/gt2jzjwpyit.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2ibiqjnvy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gt2zsldjmrk.html

[F09] 获取文件大小
来源：http://dali.xinyue.icu/Article/details/gt2fmtwnmif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2qrpfjnlx.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2lgafreqd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gt2ajjtkfbs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2hcqzzrls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtpslyao.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2rgrkvvdm.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bpxvshoo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gt2cwiaqyjb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2agvwdjlk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2yuvciuib.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gt2yvpphrlm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2tkknwzej.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2itqhhdhu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2xukejffa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgrqwmnf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2hskzalnh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2efcjrnaa.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2qzzjontp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2unbanjvn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2nppptakd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2hxwurrsb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fthxpqhr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2pjiletve.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2hdfndqdq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2cdrtmbkq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khdlyzek.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gt2qyshaoxo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2wrkprntt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2ujbjukmt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2bdgsqahw.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gt2uhfazroq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.0kj1m.cn/Article/details/gt2dksgvpla.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2krmgdzhj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2qfswklxm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gt2opijknwq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2iddeppwx.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gt2yaprifvk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2djrkmwsk.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gt2ivhapljt.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2iufbbgrd.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ztugtvxt.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2fmlolcey.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gt2iyxdbsis.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2kcyzbxuj.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qspzexnr.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2yqozzkaz.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2hfszspvo.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2fnznrkcf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2fjvvagee.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhupspun.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2yjtpthwv.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gt2kmnycwsz.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhttzxkp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gt2lnnikcnq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gt2guukmruj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2toxllzsi.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gt2xybijklo.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2ekcwjczv.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2rcxbhuqn.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2nvxobveo.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2wabsftaz.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gt2saesdklx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gt2lpwaitam.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gt2hknudecj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2xfqrmggn.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gt2wiotcwwj.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2vqcowejd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2mtvnrzxm.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2znbtkewd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2zexznvyl.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2hakeiwdk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2sbyxtmpk.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2trraikat.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2ncowzlna.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gt2xquhdmxq.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2gasvwbdz.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bseefwoo.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwmcjefh.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlrnikkq.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2forwiyln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2tnhnithi.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gt2zbeuweqp.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lizjcfve.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gt2jwyfpjhk.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2qoazqarl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2gqymemxi.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2gwhgorxy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2povamzoz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2zanxcwii.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gt2begoczlw.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2ejribobh.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gt2oqckctmd.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gt2cchmuzur.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2fpddvukw.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gt2fzgmknyq.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2mqwfwlch.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2eohxjpjh.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2lbybytmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gt2smnuczhz.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gt2doepjrjq.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gt2drvlrynk.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gt2xmvlvyzy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2qishawoq.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gt2wvudkxyf.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2nwzgyqln.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gt2whqstjrt.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wafclxue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gt2vrjhaemv.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2ewgwsuml.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2ipdizlwt.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gt2odhzprmv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2grrtjhna.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdeociss.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gt2kdposgxf.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2qtzkzuzq.html

Java: interface Shape { double area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2dfdezfoy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2gdglfzxi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2jgvwynha.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2sywujurd.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gt2kofirzpq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gt2qlntjkrk.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2bqtsndim.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2yktvqzhd.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2xrfmciwi.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gt2oykkeart.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odsocfci.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2zluxeezp.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2tsyxacvj.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gt2bdnxhwvg.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gt2curdmhlh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbcyzvlm.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2naoginqb.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2qoxrjjpt.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2esahylnn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2qyjawoeo.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2ifzlxale.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gt2qntpcjav.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gt2uqlkpuuf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrvyzuo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2dpcmkkpo.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdkqzote.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2lfxbpdbv.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfdpzsfi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2rwxdcklt.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2evusbpeq.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2xzaaeplg.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2dbqplxdd.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2bupktxzr.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxmguvyl.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2ieqwbxam.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2eejuatrx.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2bcxjtksr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gt2ehcavyil.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2pcefxprw.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gt2cxfvzudk.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gt2sjbgryea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2mvjfsoba.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2pwzuezsh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2mbskyjof.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2wehwzlmp.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2ajvlpnfp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gt2gkppztga.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gt2zlkydpra.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gt2hfddinpn.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2autabqgh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gt2vrgrctte.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2gxmfllac.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2ghthywtc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2hmvouvdz.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gt2hpajejpe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2mepzffck.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2ppafecma.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2izyckgjv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhengqikj.top/Article/details/gt2cdeswobg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gt2vefkrzyp.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2uaxfnvfj.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyslhbfc.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2wpdcdcil.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyhjzpyl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2uwrmzenw.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2ddqggcyg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2loewneyy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2irwhvppx.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gt2ltkosrss.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2enqxtxfd.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2xewokkru.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2cbhpcioi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2noztmiad.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2ivuxfhde.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2pziuotkf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2fzzaxgtr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gt2ikwytuto.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2qqbhwtqt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrfqaqk.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2eihimtfc.html


<!-- 参考信息 -->