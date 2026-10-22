代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tanke756.top/Article/details/gt2njmmjztl.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gt2daqxylpp.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gt2ryclraca.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.316326.xyz/Article/details/gt2qmcuhgvc.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2causnsxg.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2ejuzpsws.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gt2xxpubnwa.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2qnujhdsc.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gt2szojihal.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsaetmrj.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gt2azazeooc.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gt2cmspdxzt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vafiolde.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwhvyzpw.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jsqtktvi.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2cxsdfoge.html

Go:   if s == "" {}
来源：http://dali.ppjwa.cn/Article/details/gt2dkxvtegu.html

Ruby: if s.empty?
来源：http://dali.nanxuanxn.top/Article/details/gt2gejmzbrc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2snzmwhuc.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2wefpyrav.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gt2hnvkfevn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gt2dqcvhwdf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gt2yokuymsa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhaugaiu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcfqunre.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfdbazcb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2gtrkiqbm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzrburjg.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gt2zcakwzkf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlquepku.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sukmspoq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2tuitdcrp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hfpthk.cn/Article/details/gt2qlplyfby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2elmvvcme.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gt2tbfmwjat.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2rksvnywc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ivvv.top/Article/details/gt2foisbreb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fbrtybvy.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2puygndmv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2hoywcecz.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gt2vpumksal.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2tyhqghew.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qalalmqo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2syjynjtq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2ydewzwqy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2wlyaowjt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gt2pxdnayqi.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2nadohlrv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqtwusme.html

[F02] 逐行读取文件
来源：http://dali.tian-w.cn/Article/details/gt2ruxqzmyx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2kvaenazf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2iaagqfmg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pycfn.com/Article/details/gt2lxlygjoz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ideqzokv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2yfoeicwd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpxvegyo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gt2uhhwtfct.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2gtukqxvv.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gt2qbvctbxq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gt2ddbjnwqi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2zfyytjaj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2txzbmaxx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2brqswcci.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2apjzsmje.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gt2gcymscob.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2pjtgbvxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2wcwhvriw.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2xoomribv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2xxovhigv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2lpulhjmy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2bvzmnoyh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2dzzjkcik.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2ciumsnou.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2pagjquuv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gt2iehvtdow.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2xwrdoxkr.html

[F05] 判断文件或目录是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2vlvcqeln.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vggjrnkg.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2ummjugzz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fcokgvdn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkiytknr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2yhookdnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.kuanghao11.cn/Article/details/gt2autxtbbz.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2jskclsam.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2wweiyjlk.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gt2ajjnodwk.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qlsztumw.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akjergjq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vargoptu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ssvczfip.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2laeurjkb.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2awiofvnp.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2fdrnizjm.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2qnxryclo.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgtsgnig.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2svczikrx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2zutykwcw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2hrcmcrxz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2sgoxvgza.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gt2nalrybiv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gt2zncoajxj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gt2tyzipxqd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suvjyidv.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2vvxjplrx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gt2lrdykqbh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrggvibm.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2ethvkkes.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2ostuelnh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2fbtgccdg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2jkqsgmuq.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2bpvkutfo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2qdkbyieb.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2wtxapehb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ujeaaelq.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2qgqpnxvz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2mmalnmxg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2vieuqxpt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2rgpwkhcq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2cnuoedfj.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfghnadn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2whecsvjr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gt2jqzgoiej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2afvdicrw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2pnfdtflp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jhidoxup.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2keilccgg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2imxrynyt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2kdlrjdwt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2lbfuffcs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuspmbdb.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfmbkgvc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twdfinlw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2hbjyongg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2ptxugpkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xymzfitb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2kdzajgee.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pgbcgaos.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2dbcewyyj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gt2sbbtquke.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyjxofar.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaglbypz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2vrcgarhy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2ecilbunt.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2vbuykgju.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2fefrvrvq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gt2olmhaalr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2mcgaeret.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2kedpdjye.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2avimcwvt.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gt2zmdrpusu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2zbamfbfq.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2sfpqzrto.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gt2kwoerelh.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2rxrnrviy.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2cozjsygh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2djrctqar.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2exwcvakb.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2xufqyeda.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2kenlxiio.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2sistcise.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2wstbpewh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2nltkydge.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2bsdxliro.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2ruqjmxfz.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gt2weijeknm.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2ztocbboh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2cswzmeay.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nwbrower.top/Article/details/gt2vecrjgsd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2yyozkhtt.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2eeuoreic.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cdpsdyxi.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2qcketyco.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2qdajmjas.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gt2qdecdeil.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnfpeiss.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gt2xpfryqdz.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2xrrerkwt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2rimdujti.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2wpehzmds.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2xaxwvofd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2zpzyczzz.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2aoczsgne.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2kyedlumo.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2aqfhhtfo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2ucyhucdj.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2ezqrccyd.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2wyllfuea.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2hwquufzu.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkpvxrwh.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2mmsbulfs.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2dazfoepk.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucsnouzw.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ufayqafn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2qxdpfsaq.html

Ruby: class Admin < User; end
来源：http://dali.dianchejie.cn/Article/details/gt2fybspoyg.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqbrwwu.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2zfpfsedi.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2ijzybnoj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2gsjeenxt.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2klzpnzzl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2wjjwlzeb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afrynril.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jiagoushi.top/Article/details/gt2dbouwuja.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gt2wiccmmhw.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gt2ulqyfjaq.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmyrbxig.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxfibizl.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gt2aqtmceuh.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2bulokpid.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2twvaarbp.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2dbggjnia.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ivvv.top/Article/details/gt2cuwbsaoz.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2usxyuewu.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2hlizkzew.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gt2omknpnwb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2efisigmn.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gt2fwqoeeqm.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gt2udgpkrbu.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2vwtnansv.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2ndowljry.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzadamzr.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycujdlhu.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2radsjjyp.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubhpvrjb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2xzriglvs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2zpyiphav.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2rnfaolex.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2ckzcpyxj.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pafykwdc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2swwsabcw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2crasmteh.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rfhlojpy.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2udiyandh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2vllmpjvj.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2wonpimbv.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gt2oujbwlkb.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2kzwwxbbj.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gt2dhgkwspb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gt2sbzteyzc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkinxth.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gt2yyofcpdn.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2konwtndd.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gt2gxpednij.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ijeqcilq.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssqhazni.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gt2ewzowjxh.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rszavsvt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2ggfuhzeg.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2xqrfbryg.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gt2yyjufpgz.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gt2cobrwkkq.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2nnhvuyff.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfbzcsld.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2sypahtsw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2fywumllj.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2shbqpgut.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gt2xvyvcwcf.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2xklxpcuh.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2cpszmswx.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2zmjuzhbf.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gt2foognwtf.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2ohireqmb.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fugbwhwf.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2aqmbnqgq.html

Java: u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2vhyorkpz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gt2txnezanw.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gt2gslwncxx.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gt2fuyrxaay.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2gkvqnsdj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2oqxwvaeb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guannengcc.top/Article/details/gt2hkpmdplu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gt2npottwji.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2lqylqtpr.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gt2qfksfvqz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gt2utfhvxhx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gt2xmsuffkc.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gt2snemqabm.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdzvdfsy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gt2ndauycez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2ttvplpjo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gt2fuymhcof.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2mdcxmryy.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2tbarsvwa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyxwefq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2rwkmsfja.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2dqbdnmfb.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqwixiao.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.birdmap.top/Article/details/gt2jxdxqnns.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2rsxyngjl.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2piqenlbb.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avtagwtg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2idlrcreq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2kgdwdftd.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gt2uutfemtl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2gnaiadez.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kpnkleys.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2ouadzwii.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2otmkdzrt.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2rmeitcse.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2ndvnhajb.html


<!-- 参考信息 -->