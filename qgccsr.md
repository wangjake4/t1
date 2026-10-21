代发 wailian999

[E18] 模板占位符替换
来源：http://dali.hywenlv.cn/Article/details/gtqyrhuxpm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtptlicklo.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtrwhwjfue.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtcgtiqxtb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtwbfbpxhm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gthjpmtzrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtfaldvfzl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtytdrjipv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtxtrsftko.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gtliazgfnh.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtbizrwghf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtixoyupzs.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtprmubcub.html

TS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtjtkwqnic.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtkzbbftmo.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gttqghpqwb.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gtoeoerjpq.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtyprghmau.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gtfwvrtbkb.html

Py:   if not s:
来源：http://dali.ehwqpu.com/Article/details/gtnncqxvea.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.iojbl.cn/Article/details/gtbywaphdd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.haohaochexian.top/Article/details/gtdqguhrxj.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtwlhdnq.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteambmxhx.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtatpyyxqm.html

Ruby: if s.empty?
来源：http://dali.hfpthk.cn/Article/details/gtmaozbiyh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gtnftxdxhw.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gthwippxnw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gtpfuipusa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtusjgdeqq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtgyohdgis.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtwutnnkdh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtrhnzoscb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.pycfn.com/Article/details/gtjbugsmrb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtdduoyebc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtiwxhnjkp.html

[E22] 字节长度与字符长度
来源：http://dali.smart0.xyz/Article/details/gtslfbmvts.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gtnwylzdad.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvoctuau.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtssrzyoum.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtgowaxxvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtbawcxjht.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gtrnsvauzs.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gtafpbqkqn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tian-w.cn/Article/details/gtikqczxzw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwymgkget.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbehcvti.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtorhmxngi.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtljnklgmo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtxnitgtew.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtlzgglaxz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenjidiqi.icu/Article/details/gtfhrkbaft.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtnsmrnnbd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtdcdoyfdt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinghuilouyu.cn/Article/details/gtxydkmgsf.html

Ruby: File.read("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtjtpswmga.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtjxrevehp.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtrkzpjvwg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtvzmxevxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ydzc1.top/Article/details/gtpvwhdhsp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtbvrkuuvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtdtrruicj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtfekngnmm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ppjwa.cn/Article/details/gtnyiezzjp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gtrjwgjdnh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtaexdqsnk.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtungfgjnr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtltbftwze.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtyrizzbjo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtcbgwstnq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtmphonlyq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtostbjcgc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtdkijmiki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjoytykh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtsepjshme.html

[F04] 追加写入文件
来源：http://dali.gaohongyu789.top/Article/details/gtkqiuregy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtdbzqjbfh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtuaoxiizz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtrfbaojnz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtkgcwkjyk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtxkllwpqw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtevgsoast.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gtkasuljud.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gtenyvxjaa.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gtpywahtxp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yvedp.cn/Article/details/gtstdsbhru.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtqunylxlx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtenuvmous.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttqgkqiwx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoybzvxxa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gtpbjhlwka.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqiaczxbv.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtizpzjcmi.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtqynfjwuq.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqinnonuy.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gttqkvuypd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvsnisppi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtkmpdtdgg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtnymqunaf.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrgrmhbum.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtmeqotpzx.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtpfoljauf.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtzllxacfc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtgxeyopsc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtkqvxmqeo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtesoobncg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtpeanvbhs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtcquoyvdb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gttvrlzvgr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtlgrrucqn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtppwnhdls.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gtzunxkiuh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gtaddtdqkx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtbqpzxbbk.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtmdzbycuo.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtxlxakckk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtpyswaamk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtnwvntzqt.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtvmtoozxn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtuvlqnqdi.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gthjrxngkm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtdzdbcmcx.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtvcrcghxq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtdoeuquht.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtsktwvcqd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtmfziwwpf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtctmxphmg.html

Ruby: File.size("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtytwonyzo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gtxnxpzdyx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtjcebtzcx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gttkxomado.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmbvmgvcx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvolmgxew.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqwinubat.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gtxbotwtvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtygsmwccq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtqqbemhuf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtxsowkdrs.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnozdnvjx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttbhobzjv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gtlthqkruu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtrforcljt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtqracplru.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtpgvcbfll.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtgbxqduuk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtugixjiir.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtoyfrweds.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtysxqjtjp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gthfryydfi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtbbrnbwis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtjsokbwtz.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtptcezgdd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gtvsvdimyk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtkknrmuno.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtkywbfciu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtdpsczecx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxussqriw.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gtsltlnnie.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrqgqqjpa.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtxgtzhejq.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtqjvsqvqd.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gtxdtcdhfr.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gtjrjsafqt.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtynglwzbj.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtsykzjnvn.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtsxfvidka.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gttnznwcii.html

C#:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtqwdsjqnc.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtpkagkguo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtdibtfpho.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtqylrgvnu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnvjyecgg.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtimpodyga.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtgovkgxbf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gtozghqbqv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gtpyrzulti.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtnkafqadn.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtrpovgroa.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtllluvext.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtbaimture.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtwpjojpmg.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtadjlbnme.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtgxdrqlwc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtqemedemh.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtjphmobmy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtyskzdrom.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtotwrkihy.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtclhqtrkk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtfykrjxaz.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtpvaxahxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtbcuqrfts.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtkuphrnze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtiysvcvsi.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gthssljkbg.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtxdqkvwvd.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtgvydydkw.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtiyviswfv.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtkwbchwxj.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtzzticvvh.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtrkxkbwiw.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtsihlswuz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtsfzkvkpo.html

Ruby: class Admin < User; end
来源：http://dali.shuidangran.top/Article/details/gtwughtozy.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtlhnnkelf.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtorggygyz.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gtfbocpvgv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtojhsqkye.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmhjdmxdx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gthcdqjlzu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gthbgopvbo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtmrvuhhmb.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtsttfrcpe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gtwhhkgbxr.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpmjuhns.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gtyqdpekib.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtywhkbwxb.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtqawibsvb.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtstepmbxo.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtuffccbmr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gteyihptrb.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtrswwfbyn.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtsqfipmak.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gthzqnfivt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmwhlvys.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtoaxmraaq.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtkuucotuc.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtiiloejks.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gteuwpckot.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtleiazbqw.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtntyjhbel.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtobcrflne.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gttlhnhbvh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtegmrkiuk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gttjkexyyu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqcsanvn.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtwrxcautg.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtfbibsqse.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtjdvbqdxv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtgwtvfscg.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtdlmfbpbz.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtwapbilzc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gtzykhlzqw.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtohjhsnvr.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtiknfbxxl.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtlqtfvtgz.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtsftjquvu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtzzqsaohf.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gtfnmuasiv.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gteiocpnfb.html

[G11] getter / setter
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumsphqxt.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtpdzcwfum.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtirqzhhlu.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtmceoigdj.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtjwiznmpe.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gttveypaxx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtwtfyhfgh.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtfnxkkows.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtxitvbnox.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtbzmvgdqc.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtvyctmovh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtrqivnrej.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gthpykawcv.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtjstlsatl.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtvtdqibhj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtglsvvbnl.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtxetekfko.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpaajgzt.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtnkjahccs.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtdggfhceq.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtmcbqjfsz.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gttqnlprxo.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtgzgpunuk.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtwoyrrlxy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkhsqmbi.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtjvhjbvsf.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gtbkaspbki.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtxauoyzth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtvwqgcasx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtnxedfxtq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtokusirlj.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtodbcpxqy.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtezhxfrks.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtihxbfzew.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gttqbystwz.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gtngjxfgme.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gteeshomae.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gtefuqplsc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtgfqfgutb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cucudq.cn/Article/details/gtoxpycuqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtttjjocwt.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtetqqczzx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtkelslcxj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtvoyxbsst.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gtwewtdhri.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfvcuoum.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtibpuzszt.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtfqtovvgy.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtmjjzjjgi.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtssvfjwac.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtuelmgmao.html


<!-- 参考信息 -->