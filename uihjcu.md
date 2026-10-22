代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gt2obzecfqa.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rvockmak.html

Java: s.lines().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2qxnszraa.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2xqolckcy.html

Ruby: s.lines
来源：http://dali.svipenyu.cn/Article/details/gt2lfytjwzz.html

C#:   s.Split('\n')
来源：http://dali.dashuyun.cn/Article/details/gt2nxazfhjy.html

[E20] 判断字符串是否为空
来源：http://dali.ehwqpu.com/Article/details/gt2knpfcngl.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ufwqaqxu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gt2inwhuulm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gt2dhlrtgow.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gt2axfryjqw.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2psmmjuht.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gt2wwarpcqe.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gt2jwxzxmha.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ohjrkmzf.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2suqtfneh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gt2cgsjwffa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emnyvfiu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2azdanmdo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2kznapzak.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2jvmavxzr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2dlquvkli.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2tonjmyiy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2zavxgljo.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gt2kjohagbp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ahrdfojh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2aammmgir.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2oilynjvs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2hrefhhnu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2agdgypqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gt2vjzffenf.html

Ruby: s.bytesize;  s.length
来源：http://dali.hammf.cn/Article/details/gt2yegtzcpz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2wojkzdpv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2iyzgvoiz.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gt2xxfkcgdo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2hjuigewn.html

[F01] 读取整个文件
来源：http://dali.cqqwz.cn/Article/details/gt2idwtldgo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2wjjaqbcz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2loniehpd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gt2eouwanma.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2onebjbvl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2pyzswnqb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gt2lclcssfl.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxiqfwfr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2fuwtkipt.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gt2lhpgompb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2flbmlpel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oifjsxvp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2iplfrlso.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2eiauxmbt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2svvrdxxg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ivvv.top/Article/details/gt2hdezncoi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gt2axlpbats.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2hixtmucx.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gt2lncxfdfw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gt2fjujizaq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2hwupavdp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkxoaycf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2xzrmsyri.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2ngdyhnuy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gt2kehmaejr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oswzjvfe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2eujbibai.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkqgemug.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hammf.cn/Article/details/gt2izrcrsfk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2odkzuaek.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2fzgymiey.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2kotdssuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gt2nbhmdlji.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2wtghgsfn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gt2nvdjddjv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpzqqkbz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2febikuij.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gt2vlrajnyo.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2vhipawbq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2gqvdwnxc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gyszgljo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2xzpefulv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gt2cwozqzvu.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xptuvync.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2pnrrhuxi.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2ggwzcfqe.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2qcnpjrln.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2pxekzral.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ybxnlxdf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2sjpawmgu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2qphbtsbs.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2xxoezdls.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dbpstsiv.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2lflpsqqf.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gt2kkksfzvy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2vhyjsduf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ehwqpu.com/Article/details/gt2oylfxhvm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2zcokrons.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2qbrjompl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gt2zsqgcncv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gt2dfzavmui.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2neecyekf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gt2okhfrnwy.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2uusqpsjx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gt2qjosxyio.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2vicrgtvk.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2xdqdudjr.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2zldfihmq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2rjwbumye.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2vvhshxcz.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gt2vxodifdh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2llunhuev.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2bekbhgtn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2rxdaqzti.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2zqbgheit.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2kctqysqk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2fektytqe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2mwbzyeph.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gt2avkalmop.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2vzqxxcay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2brufrqvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gt2rgkqrnsg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2sbdxqlgv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2jfhqoflt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2xlianmgp.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2uhcbnjip.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmvttftz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2zafqxase.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2mgqgeqor.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2cvlggwxe.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2cpzrvrpj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ddpmsdxi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2dfghrmzu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2axucrihw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2vzmhbilt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2mrbubwnc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2qyhmhegu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dicztsuq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2wrxvvfbg.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2mltendsd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2bpsjymuo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccqlxfle.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2sjyjtqyq.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnksijb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2lbmryfsp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gt2tequprno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2akpdusso.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnflufrk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2khfynlvi.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gt2rtehiusm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2npvyvncb.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gt2thlypjqs.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gt2axvgbssa.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzzknrsj.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2ggbejigc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2zpjvcqbd.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2anxbwdlc.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2iwdftywl.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2gwyinmsh.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2gimywozc.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2frylggpw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shuidangran.top/Article/details/gt2zyazuooy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gt2gkpwknoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2czbxwvuz.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gt2noavutlf.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2tpapedse.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cucudq.cn/Article/details/gt2hcrcgylv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjggqmtc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ivsqwgil.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gt2gmjhktze.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2vwjbmlvo.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2baniuwiz.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2tvuehmii.html

TS:   name: string = "x";
来源：http://dali.xinyue.icu/Article/details/gt2pzlatfly.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gt2kzwrrsuo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gt2heyxxbza.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2qmvegumx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2krppbvfd.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mepnownb.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnnqyuro.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2cjeretfx.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2iigurrtg.html

TS:   greet(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2kqukaqrt.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2asnjlfvd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2ggjbolsd.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2uszzysjw.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhnoqanp.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2drcbxmva.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gt2fyjldhvh.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2jexbnbjn.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2jzjdtfij.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2cmcpldoe.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2rdfhagzn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gt2trhvqrvr.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amagblmu.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2pekbtycf.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2jogxkshr.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gt2lvrfmleu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2lyqmnzbj.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2bxoldglz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cyqiueui.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2siuzentc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gt2jyrpzhfo.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gt2eyytvbyt.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2tuwjglaw.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2kcmdpupd.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2xbzwqzqz.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gt2drhwrrep.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2vkmyynif.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajibmjgo.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gt2uxzuipsw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2tvhucdpo.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2hwerbnqr.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2szwfravo.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrcltyal.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2dgorfzhh.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gt2jvqkbcma.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fmqvehqu.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gt2cgtkettn.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2sprdahin.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gt2pnjrkvta.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyqlcefg.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2njachhfk.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gt2pzssgeug.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gt2twrnaqmb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gt2gpjzmyrc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2xxzzldme.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2dybpuglo.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gt2twywdkuy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2pwhedhfp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2mkesjcjt.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gt2dnxjuizg.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gt2wxumddfb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gt2jdqdkecr.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2cuuyvuwj.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2toanzwhu.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnxxmsnc.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2pjptnoar.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gt2ufdvhpnk.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2uoncnzyk.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gt2xpxpxvwh.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gt2ulgyifsy.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2kyttnddf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2fhuaoach.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pextnolp.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2xpdvyqdn.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2wnsrhubh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2hhpdnlzu.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2ztnfzpvd.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gt2quslfbll.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzlzwiat.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2mpcbxyyh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ceqiuitm.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2wyigcebh.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2xeuhiegx.html

Java: @Override public String toString() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2cgrakbul.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2unorhiel.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2duqecvez.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2ysacsznc.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2myreztvi.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2kjmomzts.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2nsdxfgtm.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2jrjqfova.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2jhswvrrb.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2hiyzmtsr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gt2olpfuwge.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktrxrjtg.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gt2lkkanajv.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gt2lttsbbsi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gt2qlgvltow.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2pzfawter.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gt2vdshhyni.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2oxekrcxc.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2ksblulys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gt2nkvzdlrx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj202588.top/Article/details/gt2oohfmlde.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvtrgzts.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2uzlfudkv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2lmiusuei.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gt2rykazpvn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gt2zmubdyuj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2iiwsktiw.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gt2izapbdit.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2lfzpsazg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2baugwohh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2ygbsvhfn.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gt2bbihwyku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gt2lrxjwzbe.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gt2bfpeeemf.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2xixliemm.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2atvlmogs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gt2lgvdvbot.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwajlyzh.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gt2ckhzldmj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2yjplftcs.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkqfuhyo.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gt2dpokjwyy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2eittndwr.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gt2npgymlpn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gt2ktkopnti.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xylfe.cn/Article/details/gt2pfolzqto.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gt2xzawuagy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2fxgjefyh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2tsepbnws.html


<!-- 参考信息 -->