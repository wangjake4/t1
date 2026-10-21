代发 wailian999

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gtartlhvdg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgfzy.top/Article/details/gtcgqbknts.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtgukyxzko.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtxplrqoin.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtsaqxgiam.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtkryhnqol.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtppcdkuqx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gtafzesqic.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangdashe.top/Article/details/gtqhtdrfxy.html

[E19] 多行文本按行拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyhblfgf.html

Py:   s.splitlines()
来源：http://dali.hysaishi.cn/Article/details/gtfwymtkax.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtioeahkrg.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtpovqjabi.html

TS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtdwkbfcho.html

Java: s.lines().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtcygmlkoy.html

Go:   strings.Split(s, "\n")
来源：http://dali.daxiang520.top/Article/details/gtkvctnaar.html

Ruby: s.lines
来源：http://dali.jyoumei.cn/Article/details/gtmpocyhcw.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gtqotyvwil.html

[E20] 判断字符串是否为空
来源：http://dali.jqgfzy.top/Article/details/gtjutlmlfr.html

Py:   if not s:
来源：http://dali.guowangkeji.top/Article/details/gtdrptdyfh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gtxxwxouoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtyxdglwml.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtlbvhynxh.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtwlmohywu.html

Go:   if s == "" {}
来源：http://dali.gogol.net.cn/Article/details/gtqlagyxcl.html

Ruby: if s.empty?
来源：http://dali.yj20258888.top/Article/details/gtwhamniqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtzsfatiny.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtqnvhegxz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigufen.top/Article/details/gtuderamat.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtgrfhfadr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtqsyvnyit.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtijlwomzt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtrauhxike.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtoglfefka.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtdxjkyoag.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtdzlfsbnq.html

[E22] 字节长度与字符长度
来源：http://dali.havefunace.top/Article/details/gtalicoyub.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yonumen.top/Article/details/gtxqyxxggz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymdysvtj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gotoacloud.top/Article/details/gtcjhhvmii.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtrpcdnphm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtkkmyfoba.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cdnleiting.top/Article/details/gtmdlaupax.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gthblcpslx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yueranfly.top/Article/details/gtnxbnibmc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkawojqbo.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtdnkbltdm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbajapgpk.html

[F01] 读取整个文件
来源：http://dali.hfpthk.cn/Article/details/gtvdfanuqq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtruqqythk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gthijiuagb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtrzgablfv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtmzrzafmw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtdfdmljnf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtaibpmfoz.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvondnnuh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukllfhac.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gtmqrivldj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gtjhdamgwc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gtgnvgmhzl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daxiang520.top/Article/details/gtubdjdqon.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gthgmkshda.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtcxnyiqyb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gtllvfsyfw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtsknnhjwa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtrmrmkquu.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtbortmdqm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zycfv.cn/Article/details/gtxjzjzblh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtbmtiumbm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtsnevwkjz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtaunpcajk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtjsteupru.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gtasvsnwno.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtjzphxtvh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtedlrkdda.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtkvqpxupu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtqmngagaj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtszjbgxkn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtvvlupnmv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtozgdqgfa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtpmfececc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtfjzqpvkb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gttdksfwxv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtrerntqwc.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrywwknkh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtjrlyhbcb.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gteosdaijn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtproamnfp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtgttywtyy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtpnogbyia.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtrxjoxlds.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gteyapwztz.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjmcgygoe.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozfoqjte.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gttvzzvubj.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gtycsfutfw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtffufmvkl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqwbxpssp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcqtuzzkz.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtipdfgxpl.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjvtdoylx.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtjgjfqbao.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gtxmnvlgxt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtcmxskvji.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtinltdlcd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtnctwftsr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtteadsalv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtkquldepp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gtmjqtgzzy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtkypikxju.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtxrvkoztm.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gtmujbqttr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtgtpfpmay.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtacxzlriz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtouaeutkg.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gteapetayp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtffetbtzw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtksqqslrm.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtwuymkdkd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtdhzgzmwn.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtgjzlrciw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtcgvqrofc.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtqrpehtcy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gtzmuugjmn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gthulsxzwj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtzawcrmfz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gtcijdzstp.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvrcolorh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtmcqhxfqr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtmkivdemn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfkqykbpm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtmvsjsazg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtknygdiqp.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gthjoeczqs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtadirfocc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtsbknrhte.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdxzyxmmp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaeglszp.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtykfxhikt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtcisttlrk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtngiibrmd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtvwmepgvk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtrwcvkizh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtpsikyghb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtfirzvfon.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlneplygw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gttqshyzgp.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtvapzinxl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtfxmahtwk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtvpmbbaiw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtfjcdoyhp.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtbajrwjaf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtyugmoyxu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtiuwhyjch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtpjkhdbkx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gttujluxnj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnjvwulzv.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtgtzbzqox.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyjutgxpv.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtjqldaqff.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyvdponi.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtiwngneno.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtcuyglelz.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkbqwiyum.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtsqcbnpqr.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtvldwnhhq.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gtwzdmhmxh.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtcevsmzfm.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmgoiztm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtllpempbh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtayasdlkx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtwpvxwssi.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvzbikksj.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtvzwkkjwn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtsdbobqlr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gtaezhqoiv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xinyue.icu/Article/details/gtcrtnghlz.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlaseeez.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gturdgrwbe.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtevbdjlpk.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gthxwviepp.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfpssrvd.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtksgszrfk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gtadimpheb.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtsstdvmkx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtkucczbmp.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpasydtyv.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtpmqbjljg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtpuidgwoo.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gthuhsgddh.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtrkhyfbpq.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtznkfxydy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtrlzzkdvo.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvmhivbi.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtfualwfjs.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtuxwenkvn.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtxhawkzac.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtrmffywwp.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtvhuwxotz.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtcxastkdt.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvhmsqsce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtzptrkuky.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtjqknkasp.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtwoicmlcs.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gtylbhraek.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gttwtlmjlz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtwyforggk.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtwikhzyic.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gttuifgomm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtjzurduti.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtrxbihgpr.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gtlobmtpft.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gteqewhleg.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtdrnxjjmj.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtaytiaalb.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtnhicqozt.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqsnqvkh.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtveyggmpa.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gtotpdvogo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxdguofj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtptfpoghq.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtrzjykcbe.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtlteenxcf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtvtklwxuf.html

PHP:  public static function f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtxwfcuxqp.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtsxotxrah.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gtwwgimvjl.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtbekqziqc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtkkozuvec.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtaovxuecf.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtdirypsod.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtwparyhzs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnwmgnwy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xinyue.icu/Article/details/gtbdpsxxxr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtdjohnfns.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtlynjsino.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtrhgidifv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtbqpooobp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtbqbiuqbh.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtfgtxtpvh.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtzrvzzzuj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtbbfnjxcn.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtnlmkyuvk.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtgutnulsp.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtbsuiqvkf.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtgqmrdknm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gthkkhyiyz.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gtkybruzxe.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtlpxrplyg.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gtdbluulwb.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtpwnrgsnr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtrcgyixzq.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtmdwcsxwh.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtjokmtmxv.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gthorjoxtx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtxvcnfigv.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtdwizelkc.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtpryimqnv.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtfgvhnket.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtyobsnrwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtbpjmnltf.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtitevonbt.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtrcpacaxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtoyicjvlt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtihhfstsj.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtrkhipvmv.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtmozmpuyg.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtehvoupjc.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gtnactgowy.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gthpwevpea.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gthcmwduwf.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtjbhkpiue.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtijsxilfu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtsebqzovn.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtkknmmqxq.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtobkozsqm.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtsafklaad.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gttyjcdbgy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtompnugpw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gteinfppgr.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtorrdeokr.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtrtmyhuye.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shuidangran.top/Article/details/gtseqyjrnw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtmekfqtwm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtpxkxdmyr.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtxtyhwiyn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gtawpsycge.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtfjroltsn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gtudmuzzys.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtjeuljsha.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gtvpnggidp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtjqujeruk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gtpelaupvg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gttneprcux.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtcfqznaii.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nwbrower.top/Article/details/gtrexhijbg.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtxlxojjwf.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtrfavbmco.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtsdaxhosx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtqziyzzoz.html


<!-- 参考信息 -->