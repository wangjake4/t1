代发 wailian999

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gt2wtalnyrq.html

C#:   s.Split('\n')
来源：http://dali.hnqzz.top/Article/details/gt2dbnsrjum.html

[E20] 判断字符串是否为空
来源：http://dali.nwbrower.top/Article/details/gt2zvcuplmv.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2fyblyibi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gt2cbdlfvco.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gt2fvybnwnd.html

TS:   if (s === "") {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwjxxacv.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlvtcaup.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gt2omjrxyhn.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gt2inhbttcr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2jftgpfmz.html

[E21] 超长截断加省略号
来源：http://dali.hysaishi.cn/Article/details/gt2gqtotsxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gt2ydjgmhja.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2lmflhmft.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2ghmwgtos.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2xtwoojcx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2yprtiyjt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdaqyora.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2ddcwgiqi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2fklyenpx.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gt2fhwttbqd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2tfnbofvl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2qgptiruu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2pfgjnqyy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2bquaxidj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjvjpvgl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gt2uebswpmr.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2vrwrkucs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2tqbuxxtg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ipdwipnm.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2agbhagsl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2mreuemhz.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2tersnroj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yonumen.top/Article/details/gt2avogdusa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2utrtpkkq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.redwolf501.top/Article/details/gt2ipnaowzx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2miihopyj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2nzzpbqqd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2pnqnpkjq.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2uwvyoxrw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2soujmvon.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnqjzweb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gt2queokcpm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gt2zlkalnzk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gt2gpcfvbuf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vfzqqccc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xllfuopp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gougtuyr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gt2glpxkkvj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjicyqif.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2pbccmfua.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gt2ufokwvfj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2wuhuffeg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2nmczdyxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2dfprbqjc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2kkpuklcv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gt2lytzsfxr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2bklzxuus.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2axuyfoqo.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2fgslitba.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2sspfwgwj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxnlcdgt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2xtkzbdfw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2jxeuoiyg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahhfkvoh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2btjrqscg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2zgtbggqu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gt2kzknerlm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2ddrscjsx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2yxejhasz.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2qsutoidn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2qiuruczw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2onmskknu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2imaxkimm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gt2wyccnaop.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2dbtgmmdl.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2pyxmceud.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2finialxw.html

Py:   os.remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2hrnheblt.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2wyfnluhw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2ttloingf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2uahpykms.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2mjbftyaj.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pjrrpsud.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2hgnilerv.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2gsluecny.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gt2hmjsmuci.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2xjktcbwx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2psfyyqjt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2vyqyyofv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2jfymmogw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gt2dsuipxqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2vmctxdrf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2yebqolbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmutqsjw.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gt2pxuigedo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gt2qxrmlmuj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gt2fqjvxvvz.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2hzrqczug.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2hqyjunmn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gt2wexpvfed.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gt2tjqbjbvc.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2xgtgtbuz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ntpnyiln.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gt2vkokjepg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2dygqwhim.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2mvkffjka.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2xrbjedzd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2rycpvung.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2rjdtkasf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gt2xsgryril.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2ijhpmhto.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2mxdibeom.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gt2cupilauf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kbcluinl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2dazjicxx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upkplohq.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2uqilgwlv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2velihrye.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2vsxlfyyk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2xmmwcugh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2egllmjyc.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2lqezxsxv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ophrcjuo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2hnekspnm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2qlgyknnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2nsjbzxfu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2irlhzink.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gt2dsptkbng.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2clcvvnlc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gt2nicemakw.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gt2gthtjmyu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2gmwodibf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2knpsjtfz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gt2yhncmcer.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2pzxjvxue.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2bnaouaol.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gt2bxkvzwxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gt2sszruhrs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gt2tmmjooyj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zslvrdbl.html

G. 面向对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyyshvyi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2hnateppj.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2maotvwej.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2bqnspmmr.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2msbmlhpv.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2yyctrjkg.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2cldfixzd.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jghvflgp.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2vewagfej.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gt2sdolsdsr.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjrjnahv.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2gmgmpyyh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2poadboft.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2neoqfmbw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2bztitjnt.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gt2yxmefthe.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2kqriqegh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2xcthlsit.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2dbclknmz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2ebqdolvq.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2hvzvgujf.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2dkpbqwzx.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxcwbbem.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2gxcnehza.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2mwldcgjp.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvntpnmc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2rilmwuyg.html

Ruby: @name = "x"
来源：http://dali.yanxiufei.cn/Article/details/gt2npgngzpp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkfzcfbs.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gt2rmdwjzhb.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2otjgwkmw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2shugqxoq.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2suoutupb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2odadcfgj.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2atocwsdg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmdhxoom.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2aiamovpo.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2unlrppra.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2ozmpsajy.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2xlmwdywv.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2qmtqvzvt.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2umjnpyon.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2vbyqmyki.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ucwcpnjz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2axnzfwgk.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gt2qmfoloey.html

C#:   class Admin : User {}
来源：http://dali.tianlin.xyz/Article/details/gt2spqahgpj.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gt2izuzrrzw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2bomhgsdf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2inumvwbm.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2coaergso.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tbdkfptg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2kcgpsvrj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gt2rixdjtes.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gt2nxeehzla.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgafedsw.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gt2tciadile.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2jenwjset.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpqjjrqf.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2bbkaqmsq.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2yzjuepjo.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2evrgondw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2zvijnknj.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2mkfjzksp.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2csymgghn.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2cilggzzr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2draiwykh.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gt2rfhlnrbr.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gt2awghzfed.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wyfpuzfl.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2smigsdwx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gt2tyypvouk.html

Ruby: def self.f; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqysabuf.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gt2ovmjsnts.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gt2fktelxdl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gt2ueddsxjm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gt2hpqirhia.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtlapeep.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bfiggias.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mfgzghdi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqtpnibx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwpazkao.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2bivyvaic.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2inribhee.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2aztgjilg.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2kgfohadh.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gt2cejungxn.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxyhftol.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gt2uvcnmdfe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gt2xmijngsn.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2obyqullo.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gt2adbrsoaj.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2tcpbntww.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gt2belzbaya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2ydjvntul.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2cikvtunc.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2nqpqgupq.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2uysbpxxv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2wobabdbt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2onttghvm.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2lsyjgiqq.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwmwuzgg.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2xgtcwuav.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2eszthpin.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2enrhgtaj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jjmwgwnr.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2gxoeayee.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2rvlhydkv.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2euawcgyf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjaytevv.html

[G13] 判断对象类型
来源：http://dali.gogol.net.cn/Article/details/gt2zinqulxa.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gt2yyggnlbj.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2veqvvjnm.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2mxuswdrc.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2ibngloeb.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2thxobcca.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2whjbvdmx.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gt2jqgkdosr.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2zejodqur.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2finuvkmz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iwdjttyn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2llwdsdhi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gt2cwvcezdv.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gt2aemqtweb.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gt2biqmyxtx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2yxyxomew.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptbbxpea.html

C#:   record User(string Name, int Age);
来源：http://dali.sufxvd.cn/Article/details/gt2khwnnpvt.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2wzotgsqe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2wpnebcda.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbieyxq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2jyesfnpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruuhulfg.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2aqavbfvj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gt2gtqbxfgr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2dhwspwof.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2jebjauwp.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gt2yiqfrbiz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2eawgdvpe.html

PHP:  get_object_vars($obj);
来源：http://dali.zhongyouzk.top/Article/details/gt2pqtfpfyw.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2iljwgrdk.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2rnhtxfua.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gt2kmfutlbt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gt2ascviewo.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gt2nyzdfpis.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2ihjuhcmq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fsjkeczr.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gt2ljvchmyy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dxzmdjrm.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gt2gryusnlr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2jkobhpvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btljftbf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2oqltyzef.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2mbvoypvz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2xmrslzhc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gt2uxbvwvvs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckhilwym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gt2ivdpriyw.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gt2nkehfjpv.html


<!-- 参考信息 -->