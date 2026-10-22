代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtkarzmygn.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtrgcxprlx.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbgaedgz.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtkohiztuh.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gthpuuurce.html

C#:   s.Split('\n')
来源：http://dali.daxiang520.top/Article/details/gtbkjrsazo.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gteooawgwe.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtyesxjuoh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cashguo.top/Article/details/gtkqoavhpu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtktbemzmr.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtwjzlnqzx.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gthlvdfrlq.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gtpzfrvveu.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtfvqqmwcx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzeauwmef.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gtyjilpdom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtttbhakri.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtlqpevjrp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtqoczifvj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtouzrehrk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtbejskqgp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtehujcmsu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtpwwpbfgb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtvbbcvwyv.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtlffmqhjq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtmvsxxtez.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtiqsmccai.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtlqjilbun.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtlsineodd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtdnwlzjom.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtkzbdykey.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtubhxcyqx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtsqrljdbd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthmqqkhsr.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gtiqrtjzfr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtshwgrsbn.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gttkomhjwe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtcmdcywsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtftkjszuj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ppjwa.cn/Article/details/gtenxjtzhn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtfkuhanee.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtntntidze.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtpuylnyss.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtludvdrnf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgulvttdo.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gtjlguanmi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtrxhzkrlt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gtrrrffqhd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtpojuebfd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtpwwwdicf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtehtqpuvk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtfmhxmpgp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqflggsi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jianghu66.top/Article/details/gtqjjabbpf.html

[F03] 写入文件（覆盖）
来源：http://dali.mhx1999.top/Article/details/gtblmjtgyl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtqbqgaiic.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtmthizgyu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtvxpswlcr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtlsmoktov.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtgraipxzc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtzqqjyxxs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gthjglmwcx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gttjobpnzp.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtcpcbqril.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtgnnuqhpy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtxghhxrlm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gttlxmicdw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpydnompt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gtgmzosomv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gttyqvrfpv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtlmvdymtn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtzswwgmgx.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gtbpcdauuv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtpexmhcbe.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gthbzggygb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtaogfbmxt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmolaaovj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjziqtzax.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtedioxvds.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtgikrxfei.html

C#:   File.Exists("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdvgpexey.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtthbrqbjs.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqvxcchce.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtvzfkyoep.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gteiggjuzk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtqiiwcteg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtzivcgktv.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtbvcggery.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthexagdgm.html

C#:   File.Delete("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtylemmhef.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtgghpgvbq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtkmipudma.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtiopblmod.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gttctvtied.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtrswyrpop.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtbjrfkgnx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtwzcgfxpr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtbpclxxpy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtnvewpvpn.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsddufsy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtqlnohbid.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtwvvemiwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzybenfx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtyfoandyh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtckeopuuh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtwxzwyelo.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtxgysevct.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtfazigwnn.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtzlutsgyo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwknytbbo.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtkrabvjbk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtrqhdazye.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gttjjixvoc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtnrshmdmt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gtypsmdlsj.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtyurnkcxm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtxmlgahcp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtmodhccvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzndrdfkl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtcvgxwqfq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtwztrdqdu.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjbvcezu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gtgqtrosnk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttakhceje.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpzkzviet.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcxlnfwrk.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtujntushz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtoucsxoet.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gtuqgufhzs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtoyyojfuv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtcnhfumzc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtbjscrekr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtqivcnmgn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtvublcchz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtxsrlpktv.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gtwujjznvq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtxyxfwzvs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gthciyovoz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gttrnbbiiu.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtbiwboiqy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtuzwjwpwt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gtflbkvzkr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtjrrkovsl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtgcxyvvag.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbpwkijjc.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gttevfrhjn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtsqvkqkfa.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtvdrfbmlc.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtzehyqqng.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtbvcyppat.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtwovfpowh.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtwlykbsjl.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtgoxpivsy.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtzodofabl.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtzkdyyssg.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyvaphla.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmxhftcbx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gttapwfgph.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtjvqikawl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gttcjbtayw.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmtetffct.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtcgblpxfd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtzbeykmet.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtemsmaxnx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtmnkkncco.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gthnrhrhfx.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtyfvgfcml.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtrgnaebju.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtqjacoqri.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtiihkymho.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtwgawqjdp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtkkphhrsx.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtzehnczlm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gttiszmdho.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtivjyjpjr.html

Py:   def greet(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtkuaqehef.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtvpgllpef.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtsyavxlpi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtqymzrsgi.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gttslojpbl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gthgzukvne.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtjrtaqkdt.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtntzouwbi.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtqbuhoyae.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtgylsdtnw.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtlhykadnb.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmuqlxyrn.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtfuplualm.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtssawxmbd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtpiibahqb.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtlzmxqckp.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtbaelbbce.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtkfnzmmrb.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtzhzwaqor.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtjkmsfbbf.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtwxtqbhog.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtjxbrpodp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtijnjkpbk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gtsnmrlkab.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtnejagqoq.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtfmlghpht.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtilccfxly.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiufsokzv.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtgkobdnbp.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtfekjcokc.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtwtzkxqcc.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtyvsniysk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwhukpex.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtilsapjtw.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtylkefhdx.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtfgiugxjd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtcztmxuvn.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gtcmfsfmtg.html

JS:   static f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtmmwttsxs.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtawbvzujl.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gtbvumrpxx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gtlobivxjm.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtvizwnqna.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtjsgbqooq.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gtukqhijez.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gthfzwjtgx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gttqoxxoml.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtikrnrqyg.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gtfuyxumcx.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpsrxioz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hongshengwenyu.top/Article/details/gtfmytzhor.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtzgwfxwbr.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtskapdgpo.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtidkxqcwn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtuaqewwja.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtrsjjbnyh.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtyfbysjrq.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtukxpjjxs.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gteyselvqa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtokdayzlp.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtqdolanyu.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtqxjvxqyb.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtugxcbaro.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gtastjbccc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gthklotsad.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtmeievman.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtxloayfzy.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtkxnfzdzw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtbgxmtdll.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gtbweglzyd.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtttyqiwfa.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtvajbhrvt.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtnhyiwlyx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtbqaqvtbl.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtwmosbmdf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtwehvleol.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtaayhhdwp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtihswdszj.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gtgcebruau.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtdspzevoq.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtykuzjxtj.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtfxqpxdbd.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtokbbsthh.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtexbfwqyu.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gthuncjzdi.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtvisckfla.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtqdngmist.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gtrkmgiaou.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gtbltzunpn.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtghoqhkfc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtkmtpxtsn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtdefsuycx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqgqwttb.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtffjokcmy.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtajaqkyvk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gtkbikldzy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtouoduhjz.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtlkvrxmse.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzusazmcd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gtvoywoakm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtwjqojvcp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtforxlpdi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtjmpunlne.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinghuilouyu.cn/Article/details/gtundsmsqb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gtdycdvlru.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daria6918.cn/Article/details/gtnitextfm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtwyqeluzt.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtnrqifvyi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cheryme.top/Article/details/gtwadapxjo.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtcmaurbpy.html

JS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtaggbavru.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtiycsdqcw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gtvdxsnyzh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtypfziyds.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gtcebilpzs.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gttpuxmlxh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxquglko.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtihlijwkf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvzkjrafb.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtvaadhxhn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtcxhxafvc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gtahlwxpsg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtxfimbbto.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gthrgwdtdw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gttwlynfdq.html


<!-- 参考信息 -->