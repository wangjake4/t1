代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtuzgoxyxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gtrgrbiywd.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtgmwxtviq.html

Go:   strings.Split(s, "\n")
来源：http://dali.guannengcc.top/Article/details/gtakdjuhzc.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gtzsuayzgt.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gtdldtktex.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtmpkvsbfs.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokiutxgx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gtkhqbkchp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gtbuinjytp.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtdixjovln.html

Java: if (s.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtxjwvnfxv.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtflebypxp.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlzxchvk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtyzvxcida.html

[E21] 超长截断加省略号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdwtwhqu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtsmucluuo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtuoahrfsd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtdrlwvrwq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtbwyapkkr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gteusrgzrd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj20258.top/Article/details/gtozrgildt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtuacpqwzk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtkbhwjejs.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gticxoismg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gtjjuzgzwc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtaerwkaui.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtbvletckf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtxvdhcrlz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gtdduqmiqd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.chenjidiqi.icu/Article/details/gthpjqtgyp.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtewtyjihb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daria6918.cn/Article/details/gtxbsqtvxq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyxspawql.html

F. 文件与目录
来源：http://dali.pycfn.com/Article/details/gtcnowzavm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwxudspom.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gtfovrfpqo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gtgxrgjarj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtmhcvkdrt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtfaayjaab.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtrgslsssy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtiryqwebi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtvelpzxcr.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtuzlwjeab.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtrbccngfe.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtrpljmtpx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtkzajtmhh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnqzz.top/Article/details/gtbsaapnbl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtorcpvuxk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtoxstkfnm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tanke756.top/Article/details/gtyqcuvpcu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtkswlstxx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gtcfqthrkz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtqabwrusb.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtaowzggfp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.iojbl.cn/Article/details/gtqlhazyif.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gttyewkwrd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtsxkqpbld.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtaldyirld.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtpiprwxfy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtduwbblhn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtquagymkh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtztszvcgm.html

[F04] 追加写入文件
来源：http://dali.zhengqikj.top/Article/details/gtoihjrpyt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtffjigpev.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtmfuxmskv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtuurfhdcw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtegrwjifz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gtplsdaguq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsrnqogu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gtymwpzcwl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gtwqqyjvgx.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj202588.top/Article/details/gtlssucryx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtcyrkjnyl.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtagtutvjh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtujnzjdcn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gthjmgicbb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtbqncgtzv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gtpdjstpyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrdqchenn.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthzmycvgr.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gteoozjoau.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtuobbmjec.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtfrpnqrqz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtyzxbsqhg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbtlvxjxb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtfyonnoby.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtytyghwmt.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnvltifry.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtkrijybdf.html

[F07] 创建目录（含多级）
来源：http://dali.nwbrower.top/Article/details/gttfulcxiq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gtrsthhxae.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtlspwlmsl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtjezvjuxp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gthkzarnlb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtehhhzsjp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtneqyiqrt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtbolrbokm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtfbpxwzuk.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtdsijglci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnqzz.top/Article/details/gtyiztvroq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtksdqhybx.html

JS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtwnpdufje.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtohfflfwl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtqdcvsqhn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtwdsmrfbd.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtanfzkpeo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtyahosmkj.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gtburnybuc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtboquxcpc.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtdkailrpo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangshuangyany.cn/Article/details/gtyevcxvvd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gthdaspolz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtdzgmesbi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtlmrdhxil.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkngpxfrh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtgftnhemj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtjkizmusu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpalypzmc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtiwktopva.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtyvzjuxvn.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsyeesbpe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtampjxjii.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtajbjbxwp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtktvyaier.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkwbigghy.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtyeyzhnbj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyvcwigu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gttdvpzprz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtubgwrwoy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgaknmtzj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdqlxkpj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtwayhnijf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtnswpkqpq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtbhhcilcr.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gtjcenuaot.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtjwkhxuym.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtxejklvls.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtvboxchyj.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gtaixskjqk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gtuzagtrlv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gttodwdvsr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gtvtvwupsd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouudngib.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtujsoxwsc.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtcpsebspy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttjlijsgr.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtzzykgzqp.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gttjmxxhkx.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gtompymrwq.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtspxzstzj.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtlafbpvcy.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtyftshfmc.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtvvzglwmd.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gteatougbi.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtmvgdrqph.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtzzvhpeka.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtyslkstgu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxalszatz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrqhvckq.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtajxxzxpn.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtsknbzjus.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gtqzdnlahd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywfqrqdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpwrznre.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtywmwelbe.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtlwrfeupp.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtsxmuwgsj.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gtvhztszxh.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtdkaisajm.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtzojcpfup.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtkxvidjgl.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtmujjowsj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtgugtvykv.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gtiznuvexh.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtvtkoaiah.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtgjklelol.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtmdhaljqs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gthcoxeudl.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtguwwqson.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuynrmer.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtvsognqjp.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gthhwfcvhu.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gttumeeylv.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtiujihaep.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtkygvllyp.html

JS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtromgluxz.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtodukjqge.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtodabtepu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtndtivihw.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtorlkcacw.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiattcisc.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtepaexkqn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gtvxighjyr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtqrgldcap.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtnvdklbpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtaoxgcfdd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gthbbaqhbr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtmawgqxmm.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtdkcxuhcr.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtidseuprv.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtfdbxxynw.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtqilxyrgn.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtjtqbakkh.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtwitamako.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtgjdudbvu.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtfqrnqogi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtzqehfveu.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtpjeszgng.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtiotobhca.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtyygfirhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtuncfcfdt.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtltlleydg.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gttpwowcgh.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtpdcopkdx.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtprcaklxd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtdartmohd.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtjuuxnzqt.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqhyzdrop.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtyfevgkyu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtresxnrje.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtqxkczssr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtbtflxzge.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtrqcgjkto.html

Java: interface Shape { double area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtecqnqkcw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtiswmiike.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtprjuscrn.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gthxgxwihr.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtwjbivagf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtjvuegzgg.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtdngcfbyq.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gthvoelvmo.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtdkhhecat.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtncavqvmo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtzgjfcwnj.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtvcsopyqp.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtvfdnavaj.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygkbugjp.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtajqwyksd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtdjywsbfm.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtrnzysksl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfrsyencj.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtlahpbbgs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtyxrgojaf.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtzxcvojpn.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqptsafh.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtkpadnzlo.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtggxfmqrh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtmphucmxy.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtswxmrquu.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtjzpqykha.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttpqthbjq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtnetrptza.html

Ruby: def to_s; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtmbrsuzth.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtvmrixzmm.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtmkuilmky.html

Py:   isinstance(u, User)
来源：http://dali.9152youxi.cn/Article/details/gtcbcxexba.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtktddkpra.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtkgzprjqy.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtxxhwtiar.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtnczhlpbp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtifgtntio.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gthmugmcjc.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuaannny.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtwlsqybyh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtuyftvclq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtxhmpoxlt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gtcywjlyqf.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtcwkdupmm.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfxixfnwv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtnmaboihf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtuncyjhni.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gtordvhcwk.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtbpkdmqlc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtjhkswovs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gtdrtpzkky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gttyyizplm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gtashicjxj.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtadmvubyu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtgghplnmi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gtrntckjmg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtnfctghmg.html

[G16] 对象转数组 / 字典
来源：http://dali.hysaishi.cn/Article/details/gttoscgrux.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtuwlkzmnx.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gtoiwnhhtg.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtqvhjiyku.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtimczyjpy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtwdhayxey.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtfxglcari.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gthtwmsibo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtzpegceey.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmppvybwc.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gteuanlsnc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxfttgmur.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtpvchhvwl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtqnjzcgmb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gtwwahoxws.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtktxbpahf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtnnuhgmnz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtfczcetig.html


<!-- 参考信息 -->