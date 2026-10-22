代发 wailian999

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2qnldidua.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwmsqxmv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bxbilcbm.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2qqefafak.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.mhx1999.top/Article/details/gt2dxdsnjkz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpaykzkm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2cahcokpy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2lakttnhp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2mbhhajgq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gt2qqjmskhw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2xjokwxqs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2mrpdxllv.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyyvjhnw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2xvkgnxai.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwyqgupx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpiocatb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2vzgcqpuc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2uuixhakq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gt2dztldqpi.html

Ruby: s.bytesize;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2khsqryel.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2dgdydavz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvezdjey.html

F. 文件与目录
来源：http://dali.xuanzx.com/Article/details/gt2zkkagoat.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2wvhbfjui.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2fovzanvq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gt2xontqizg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2pbrllvhb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gt2skhsfayu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2yahpstyh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2hoskylsd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2ukdaoadr.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ixobnygv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2xayxugjv.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gt2pllbnvez.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gt2lszzepza.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfoyoxyt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2oioxkwlz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtxgqkvh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzpkysfs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gt2qyuqroau.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrfrigwb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chskambs.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gt2ktaetzfv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gt2qpowahjz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2qcptgqwj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2nftmpkqz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gt2muimxwix.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2karqvcua.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2ldymrwut.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2dzukwedp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2iifpqkfl.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2autoibnr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daxiang520.top/Article/details/gt2zobcrnfy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2vhdrsjus.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2tpstmhyv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2hvzpypth.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gt2ooxsysmf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2fmffagfg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gt2lirjidyk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2xxqonwpi.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2dukmefxb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2kcoijwqz.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2akmbqurm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzbbcrdn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ufeqtsxz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ebmimeub.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gt2nvujmiuk.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2yiyefxqc.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2xuiqxvzl.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gt2csdmjdlc.html

Py:   os.remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vijnccrc.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2cfpxgwcg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2pzytyyjl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2iybvzmjq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2dagrlqqt.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2xpuzjeyn.html

Ruby: File.delete("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2fyakpmcg.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2tslsrxtr.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2bccxjnjf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gt2jbqxcsez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2hdlauykf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hongshengwenyu.top/Article/details/gt2blcunigx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2cygmlbun.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.havefunace.top/Article/details/gt2naqynghz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrelvvao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gt2sfmpvxgb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gt2jsnzseua.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2vauefbfv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gt2quwmitlq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gt2qlwurgoq.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddprytbf.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2noxufjni.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2ggnmrkey.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqvukxij.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2ndeefsaj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdwpvnyv.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gt2bgebbmet.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2qgaunatq.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ufjndwxy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2qkysylht.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2xzdiifmz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2ngcevivt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2erjrktbf.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lawazriu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gt2xbipzslb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gt2mjwtkxon.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2seamdwvq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2zvabcakc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2jiuvksdl.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zedemloe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gt2gqvxynwq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2mxqddbdr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2uqunitjk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2lchbprun.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2jdlnduwg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2fshutrtr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2nxjswmqf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2bqnkkinp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2zvkpodst.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2drmzaozh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gt2autizxvd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2btlgnbic.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asxqtvec.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2ojzgncaw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2tgbtkuvw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gt2dhsryzdk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gt2diaeukmy.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2xqcjrtni.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gt2joajopip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2vipugksg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gt2mbhmzcwu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gt2lqhteyqi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sluypviz.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2ajknfgvx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqkzsdbw.html

[G01] 定义类
来源：http://dali.hysaishi.cn/Article/details/gt2atjpazyr.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkuavprr.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2fgdzdbro.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2kysjmjws.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ohrzkwgy.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gt2ayviunlq.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2exjoukco.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpytxsrb.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2jdzpkqxu.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2qumhfwzq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2sdyejvon.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2egqvvqiv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaxqbrfy.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2rxtvjchp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fazalknx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2bzmiqjgq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gt2wwhbyfof.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2zqljkdgu.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2srhqvmrj.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2jffptnqr.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fofxkjaq.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2ymbcthtc.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2akmnxhwp.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2jowyxtgo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2pheqfecv.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2qvcvavhb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2phndnswl.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2scwzhfny.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2izsqwylc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2fcgnalbc.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2xnmpdgoz.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2igupwzoa.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2toqtreat.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2tljishra.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2defxlsdl.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2ngfnmobu.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqvtkaha.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gt2tfzyaaaf.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2nrxwleqx.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2iobmqvqv.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2lporqdom.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2bhklgnel.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gt2icrkfiyt.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnfyoavh.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gt2wvralmxn.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gt2ikhunmbu.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2jnjvhyyr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2sclznnun.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2jtxgvbdj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqhterqi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2nkqqlokm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gt2xhowrvdj.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2kcauqldq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2lomamxih.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2purztbia.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2vjpgxncw.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2xuzbdulw.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2lbcwkraj.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2ytbwjmws.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2ymignnyx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gt2ngfddqxx.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gt2gulftxyd.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxvpwuyw.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gt2mgohemtz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gt2tnxatjdz.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gt2svkhgymy.html

JS:   static f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abhkpyrf.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2olrmzllb.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2milvegkq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2mdfcofax.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gt2wfekzqvv.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2cpkmzsfu.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gt2ezlchewk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gt2lcsyduxw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gt2pludzikx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2yizszfzt.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2owpnkohp.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2adurjkja.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gt2gprgjfqh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2eigygnjq.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2xvtufzpt.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gt2iphzrthc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gt2tfevmqhk.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2eybylyep.html

JS:   #private 字段；其余公开
来源：http://dali.meibo888.top/Article/details/gt2ydgvxcpv.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmlfqyra.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2lsfgnedk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2ostimtlh.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2pdybqutt.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gt2eilyxqwm.html

[G11] getter / setter
来源：http://dali.havefunace.top/Article/details/gt2jkbqynao.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2fttryecj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdmrmrfm.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2nsbnlvnc.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vuivvxkb.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2kldspiew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2bxrktrrj.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2wvhxxnkh.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytjqocsq.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gt2mfzaydof.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvhxhepi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2lpenmmzg.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fktmedmp.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2pwxgptnh.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2lnvpbxbz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2qxsxmerq.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2pfjnszyw.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2wqaetxxq.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gt2jxsxednk.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2akvpibhi.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2rywrweda.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2qhhffawp.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2aplmxooy.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2mkkmhwah.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2mghkzodm.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gt2qhmpnadv.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gt2dlllqkou.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gt2nvlnbeag.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2nlgtybga.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gt2powlwcyl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubnwmxaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gt2ilbetzuk.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2khqbacbk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2wcivafnk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2zqtvrfvb.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2ynclpitx.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2afrfoeoc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gt2qpzcdlbf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2bmrelnbn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gt2nbvsmyfy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2fdbygjfv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gt2hthicenj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpffxeje.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gt2xewnkmno.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2njkbrlse.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gibpguxp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigufen.top/Article/details/gt2vvcexxmg.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2rgfvpmna.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2ftlokriu.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2edqnctjd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gt2scgowghh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2zkbssnwl.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgpscyio.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2aiulbirs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qzpgyzjy.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2khrxbydi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ntrqpxsv.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2swjdaghz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2onpdfboi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2yilwjevx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2axstbloh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2evdggmjz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2vildvzir.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2quoatvxt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gt2eayrflft.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2kamktrrk.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2atlfzezq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvjfzkyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2azdevimg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2cstyxobu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2sqjbrfli.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2gvzqwjyx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gt2bwoqsuif.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zycfv.cn/Article/details/gt2tuzjkfsu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2terflumn.html


<!-- 参考信息 -->