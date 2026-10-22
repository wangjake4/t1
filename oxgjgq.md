代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cqqwz.cn/Article/details/gt2ufszeqdd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gt2llpeavhb.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mugczsve.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ubmqzuxa.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtdhauxv.html

Ruby: if s.empty?
来源：http://dali.yuanzhike.top/Article/details/gt2xotuyzhz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2uobzrdcu.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gt2ffrkchip.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2mreivfnf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqzhljcj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2jofcdcbr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2vxvwrlje.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2mcrcdozu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axjmvunz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2ferriiul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2msuhtgqt.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2pcqxqqps.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jiagoushi.top/Article/details/gt2jcvifekz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2fjmzbgwq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gt2ipsdojkv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2uqitrrqt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gt2huglmhod.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2psymwqiq.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenlongwang.top/Article/details/gt2ypmigmlh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gt2eitlslyn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2txwqbzck.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymzozras.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vtrppnhv.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2ybtbxnoc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gt2ytscoafb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2uewtwqgr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gt2gmjtlkus.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2hvrgigrc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbbyqmho.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenjidiqi.icu/Article/details/gt2obppbhov.html

Ruby: File.read("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2gqrlehxg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2fbelphku.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2zutqqkee.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gt2eovzjimw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.c1oappe.top/Article/details/gt2oymzemet.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2iwiqwgct.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2erbssfqs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aihndcqd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndjpuxoc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gt2sorwtjrf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2uwfyawck.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2qfrrubdg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpikxpbj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2utepcmwq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtdwufq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzmyimyf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2snxwaubo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2qqvuoawa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gt2mdmujcsm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2gdwskekx.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gt2tvptkeky.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2gvdvratd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2zqeieeky.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gt2yhmadwpa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2vdyibawl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gt2lxuraxsh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2hfunhyfe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdeurxze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2ipzlxxly.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2xdvxvixf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzilceid.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2uhmsiuaz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ubfmdinf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2yjoofbct.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2zejglpqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2xcmvbftw.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2movqdnos.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2znktmbtx.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gt2ztfaesoc.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ssogpjfz.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyizphdg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjdanbkt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2yawmjdtu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmfprywg.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2dzahcdmm.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2swoeriwy.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2ybxoyihe.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2tnfvcnwh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqzctdxh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gt2irnrrfhy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2ooklzyiv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlwfioli.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlnuroua.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2zgzxwjwf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gt2bwdoyzcg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gt2qaintuux.html

[F08] 遍历目录
来源：http://dali.yj20258888.top/Article/details/gt2bixzfmix.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gt2juqaohgg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gt2eejuwvkz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2ltookbcf.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2jfqowiyt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxqkjlhq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gt2awmyvdip.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2vjeaaljc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2ydbuukzr.html

[F09] 获取文件大小
来源：http://dali.hysaishi.cn/Article/details/gt2ekqfsxop.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wsacqxmf.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2pmdbdghr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2altjbyud.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2ujzirmew.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2nbnsvfqe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gt2xmokqgpl.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2agodjzdw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2xvofense.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.kuanghao11.cn/Article/details/gt2hsjiiurw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2cbgvxncf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2zhcilpyo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2wqigbgph.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfkbqenw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2zkdmyauy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhbnkqir.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vqwgtqrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2wqfqtgio.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gt2iylezqth.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2zubtpwzs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2jdeikphw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnwvptl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jipgrwix.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2lativygl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gt2dcwcolue.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2dksdijlv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2ohcdkpds.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2fgydahwx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2tbyookgt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gt2dapapwcm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnccidnm.html

TS:   // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2yothzjtc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gt2bmbaurtu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2xnobaebu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2hvxzumqp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2jiltuecc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2qmuhfrmy.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2orwstawh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rxrbebdt.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gt2aybptvvm.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2ljqghxbl.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhzwgqob.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ulriswqg.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2khxcusfq.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdhopuvp.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhhoweuz.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2nynevncn.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2tcshcsff.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2oujdtacb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2zqlexcxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gt2safihjtu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2xluaiirt.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2adpnbbxz.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yfydkbqc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2uomjjrpp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gt2vgenkebo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgtijnto.html

[G03] 实例属性
来源：http://dali.gzhubu.top/Article/details/gt2uhhokwzn.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gt2ziygpwdg.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2nnznqvgm.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egjvqqze.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2lqkpmclb.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gt2hoflfioa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2gygbxgmy.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2qydxhepv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2kfexxoxy.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gt2gxvpvmss.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2zgswtqzu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzflbdfc.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2eirulpil.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2sfhbmamj.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hvgjcrej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mftwewod.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2zlhdbfhz.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2cldxyjos.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2kfvwbsno.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2yjycpbvt.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2niwmhqxb.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2jiqogiyl.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2lqosxgbb.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xaujzvjr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daxiang520.top/Article/details/gt2vzbsuhgy.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2wcntmjgh.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2vcjafswi.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gt2imxeoxax.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2ejcwruze.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2qfftnztl.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2lbqdnubq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2dscewlyi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2qexlozkr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gt2bbrfurvn.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2okgdbqfh.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2aighvvlf.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2qufbehlf.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gt2suvodqsl.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gt2dnyhqlye.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2aeftrnba.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2tehqxizs.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2qklqclju.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2psobsnwp.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2tsyabkox.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gt2azyiinlk.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2vjoqpfhn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2xqwkqmjw.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhkfwqrz.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2gaqpmpxr.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gt2qbgxkivc.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2dfbqfdxn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrnwlhgb.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gt2rkvajtvf.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlavjnpf.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2oembooka.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gt2lxeukzmd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2spsgvzuf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gt2ytiadteq.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2njliwmnt.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mnqwnfqp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2xqrjxrhg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2lyukyyib.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2jsgrdqzz.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gt2bdclvaai.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gt2jympxusc.html

PHP:  public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2vmyqfizn.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2aljioavd.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2thnfempe.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gt2yrvxrqjt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2hoqyrxye.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2qxwqxbhi.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gt2bbjsxujp.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2dfndoeta.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gt2utncppjj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2rmgtcwwf.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sbnqhzhj.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2kndawmhk.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2evnkjedu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2pepcyfqi.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lywjcxfs.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2utlxuowy.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gt2ccgfajae.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2dmxhkmgs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2sbpqkoxd.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ktcdptep.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2maornxxu.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kcygtxal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajhxhoyu.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gt2ptlapsfz.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2kroatpto.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2jekffvbh.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gt2qxplxxyo.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2cekgmfcf.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2jnutsdqv.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2papoqmwv.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2jyvsxbsa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gt2knxarzrk.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gt2kpiqosau.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gt2rwxsrsuf.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2aguonktz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2uckzlfic.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsklgocb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gt2xkkiogta.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isobcmio.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2mhpbqjbk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2mejongsj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gt2rvhffxah.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gt2kedchmpo.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tiqdqkwc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2iiiniszf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gt2evbtsjse.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2sjwaddku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2tbfztsfv.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2cytdognu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gt2cdnurcxw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2lrlmmbsf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2zlkdrvrs.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2eheyddhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2giqijupm.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2bhkgkzup.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hsdwuxxu.html

TS:   Object.entries(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2eggjliro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2cjyufqbo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gt2axqdhksm.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2wbglvynb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gt2pslcjsio.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntelcerg.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywisiowj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2niqppphv.html

[H01] try / catch 基础
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilnfnzut.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gt2eoftbcwq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uesobgqk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2fxznqslx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2qolpvcmp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gt2skxdruso.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gt2blsugftv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gt2yzlbdbwe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2vxcmusgd.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2lnsnuouz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2yltzgmjj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2enzklidj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2huiywmza.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2xjqysetr.html


<!-- 参考信息 -->