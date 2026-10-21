代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtsiobrrvt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtojlzeapa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyoukdxg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtjwrwkoua.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yuxming.cn/Article/details/gtrstsotoh.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtizmyqyoh.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtvmkdbsqj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtzbdhifyu.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcwrfssy.html

TS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtkrodpkhl.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtzmqumsvz.html

Go:   strings.Split(s, "\n")
来源：http://dali.daria6918.cn/Article/details/gtwwaaekqs.html

Ruby: s.lines
来源：http://dali.chenjidiqi.icu/Article/details/gtkscbbksa.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gtqflrlnec.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtegkxvvnj.html

Py:   if not s:
来源：http://dali.jinqigfzy.top/Article/details/gtelamjvtm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwgfzqat.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yangfankeji.com/Article/details/gtkacfhlgy.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtipiqikba.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtnzzvitvs.html

Go:   if s == "" {}
来源：http://dali.ehwqpu.com/Article/details/gtbbpdompt.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtzemkumfb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvltaaukq.html

[E21] 超长截断加省略号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpdyrkgh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jinqigfzy.top/Article/details/gtlgovmyoo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtnsyqlqrm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjguattno.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.iojbl.cn/Article/details/gtmbembfsl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gthjlmgvml.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gtnmdbpyhm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtjlryksoa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtqqtsvnyi.html

[E22] 字节长度与字符长度
来源：http://dali.svipenyu.cn/Article/details/gtpyldqnfc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtthxufgsf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtzowtdgam.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gthycgsoul.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtlkjtgfez.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtmwtjwkkj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gtqxnbalnl.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtorvbxxxy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtpmdodcdd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuxsdbcvb.html

F. 文件与目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfdpizfa.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvvphlfyw.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtkupmpuof.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhongyouzk.top/Article/details/gtrsgxhkku.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtxwlarzal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gtdpqmxeoh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtweizjcjf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtjqiubrtf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtdlbfanvu.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gttjbpcdkk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtacwczltb.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtqjgfuefh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.kuanghao11.cn/Article/details/gttihaahel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtidkfhklk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtrrxtbjfw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtfvhoxxsr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtshujaufz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtxpcsqhdr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gteceykvls.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.kuanghao11.cn/Article/details/gtxxnlbuna.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtqisiwbdb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtwlforwqw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtfjtryiuw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtkpcmbdtk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtwpkjuoub.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwsyatxl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.birdmap.top/Article/details/gttqbdbgsw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gtlfdaeeau.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtgbdkbshh.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtapnzzhyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtvlegihvu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfgctioa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gteufytbse.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gttyfdvchl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gthdhgqyfo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtqcgffksn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtdgtbqekr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqvnoboe.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtvxgwtrmy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gtldfxagln.html

PHP:  file_exists("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtikfkxmdu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtagiygoue.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrnrkhyze.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtfqweiffz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtuunmzkqb.html

Ruby: File.exist?("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdgwgyphe.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxinsxhca.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtkejyhqwz.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloyzvjjv.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gteaojjnks.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgoqfbwhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtytvifkyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gthcmaeylk.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbarckrxj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtvznkfcht.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gteqxalwdf.html

[F07] 创建目录（含多级）
来源：http://dali.hnxiangtu.top/Article/details/gtsolpqifo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtnfjerdai.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtwfzgwjux.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtdvbzfxzi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtxtucdbba.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtbutrzkgh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtoxthvcmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtcxvvnwzf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhyzqmoa.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtnuihkuek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtrmszvdyi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtepduocwk.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtjkerfobr.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gtkacbipaz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtuczscumj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtjtareegy.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtrffzzmlr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtvkeypkwp.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtglcjxbgo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtalnbwgjp.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtldzqvuqp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gtwfxjsznz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtrcgzxsdx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtmhpykedj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gthmkmihxs.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnqclxhyr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtftpqvwex.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvxrvehc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttzyizlaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtxwbfcilx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuaxxaynw.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtclhmkutq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gteeecbfdp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtjhrwssjq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmwatgfsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdvwyvghi.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtcsjydeql.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtjpsnxcdg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtvijjawoe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqkuaxwri.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttifqwawf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtzjygqvny.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gtvlvnxxmy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtwnhywwsa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtsyhmasuf.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtumprrmbh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtrmdasitu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtkwldzsmm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtvqvoypxy.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtagiumcrx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gttbhzbodc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtvrtlwazk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtmgjjqtrs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtugixapxg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcstcjsce.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotzszufb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlehmrigd.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtkvjfmjyk.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtwszisxhj.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtcvywnrft.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtsneythqy.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtrlhbasft.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gtpdjdzgzb.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtcubfigkm.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtqgxperbv.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtobndwbvo.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtssvxiduw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlqafnym.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtliwjoklv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtmwfhgqjp.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtktqzxmii.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtqnxvzohy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtnifrdmfq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtunwngdgo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtpzsmguzk.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gtvwewcazg.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtlumppeeq.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtcnfdsbqd.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtnbruymzx.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtlobaybbm.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtlummjwdx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtcniezywt.html

Ruby: @name = "x"
来源：http://dali.yuxming.cn/Article/details/gthfoahxlp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkophbpz.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtoxilizxm.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtyqgjkmor.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtluqpuhxc.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtfpchghlq.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtkmtnvrmw.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtpvzbudze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtcthcxolz.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtsveglbpe.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gthtcruvhi.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtnjuwfcpm.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gttakqyjlq.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtarenpyzz.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gteoqujbfc.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtpelxunya.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcwdepkpp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtelfthyjj.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtfffqwaha.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtbqufpjlt.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gtmcraxxqt.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gtfbitgwos.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtzpirkmgw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtryuxxusg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtnpquwuix.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtfomhaobl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtncdubjjz.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtaqgbtmfj.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtqnwoxtzg.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtfbrbsjnn.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkfrqxgl.html

PHP:  parent::greet();
来源：http://dali.jqgfzy.top/Article/details/gtejrhqozl.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtjuswsbol.html

TS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtdrsrfsux.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtdduxieqm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtzwjbfdos.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtzkzzppaa.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtpoyldxsq.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtaiivewjp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gttpcoomki.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtgstwsjjo.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtewrdqklk.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtsnlnuldy.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gtghnpnogo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtnyzrdlja.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtngolrlrf.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtpvfnqirp.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtvzgsopey.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gtaxekgtef.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtobxjvzoc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtfbfeczbs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtfynamepj.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdxfsfla.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtsypwasqv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmfmyaqv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtkkqesvsa.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtlthedfol.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gtfntyvdup.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtmkdtwguv.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtolijnxmr.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtslflxyea.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtptrjhvve.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxmcdrbk.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtddyttthy.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gthvxjfris.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gtrloddkvb.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gthfwpfvsu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtbqrnwowo.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtmzquikuz.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtykdosfdg.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwwkuylnr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtnqxswdvr.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtvdvddzrp.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtybnowxdz.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtydjmwtyc.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyntthdgu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtaxcjagde.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtninpzuhk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtnmvzmevx.html

Java: @Override public String toString() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gttroigzjs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtpnuivodz.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gthggiegss.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtuuqzytfy.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtsbyomptj.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtolluxzgd.html

PHP:  $u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpqlisgr.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtvdwgchhg.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtqwilbpci.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gteefmmwio.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gticrrfurv.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtymavdudo.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtxcupcyyo.html

[G14] 数据类 / record
来源：http://dali.chenzaomai.com/Article/details/gtycucoldu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtwzhusnnb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtdkltdgzx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtkahtagol.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtpnswhyvb.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtdcvfuczq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtmsjpyzzr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtmljyimsb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtkgumatxt.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtpjuhbipa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtrmloppsp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtnhnycbyb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtbrxxkcsa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtewipligy.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemxabavj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtzkhpwymz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gtscixfvhz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeuwauod.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapdggfqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gtjpwgfjbc.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gteqoeaafj.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtxtubpnoc.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtunyknzzq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtizofpnvn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gtfurosgpw.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtxyxbwjhz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtwueooagi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtutuzwfjw.html


<!-- 参考信息 -->