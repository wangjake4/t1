代发 wailian999

[E18] 模板占位符替换
来源：http://dali.haohaochexian.top/Article/details/gtiboihvqp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtthmsdomn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtbxfnworf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtzfczvdop.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gthtexmybd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtwemigtno.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yongpay.top/Article/details/gtyxdthmxn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gtfvusrugg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gttvmttyea.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gtggbsaqpi.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtiokhtpbw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtbyopycyo.html

JS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtirxrjone.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtmmidnimv.html

Java: s.lines().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtssexqwki.html

Go:   strings.Split(s, "\n")
来源：http://dali.sufxvd.cn/Article/details/gtumpfjrgi.html

Ruby: s.lines
来源：http://dali.yonumen.top/Article/details/gtxsondcux.html

C#:   s.Split('\n')
来源：http://dali.jqgufenzy.top/Article/details/gtvxkoqwjr.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gtzielkrep.html

Py:   if not s:
来源：http://dali.pycfn.com/Article/details/gtahfmqmht.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gtddrzpbpn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gtpnkiylyi.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtotprphbp.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gtzkprmlji.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtnhpugkcj.html

Ruby: if s.empty?
来源：http://dali.redwolf501.top/Article/details/gtuwqtpnac.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gthfwdrhms.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtvnodaefy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtuzjbiunc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtdaoxyfzv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtekgpcwsv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtherlqxho.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtedqjhqhk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenlongwang.top/Article/details/gtdsmfzzay.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtqfcmfhbl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtwcqsklav.html

[E22] 字节长度与字符长度
来源：http://dali.xziqi.cn/Article/details/gtolewulfn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbxrzcbg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiptbrshb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtpiskzbah.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtmkuqoowi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtvacavndf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyufkdksk.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtpaybvzpw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gthgotktlw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtroaqpotx.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gtwyafabfe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtejtuitjx.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtljpeznnt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gtanqwufsn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gttxypslwf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nanxuanxn.top/Article/details/gtyijfwzaq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtvtjjjfzs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtgoymjoxh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gogol.net.cn/Article/details/gtywatunjn.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmnziqwbu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtquqovxhy.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gtnxpeqbkz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjqiosxz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtdccajnwm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtpykvoetg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwqdooyd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtiroxbwsq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.smart0.xyz/Article/details/gtgqzdmnek.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sweek.top/Article/details/gtwnodwtyh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtufjrzcxr.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gthfqqjojn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtunoooqnr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtjfsvsefy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtjfkspqzm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtusqkjsai.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtsxpolikx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtyymgckcp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtjiswggfx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtykescrsu.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtgknyqddf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtzwheukrd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtbmwzcavh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtwmjthjjz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtrzimbrhu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtspptdvif.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtdxloavtw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtiuoilllw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtxextnxho.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtdnvaphch.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtocvqxidt.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtdoppvkni.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtxtxcjumf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtbulfjndc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtuxkjzujd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtqttiwrdu.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtnkowehzr.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqbfrmrtq.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtsphvxxyh.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqdsprjcl.html

PHP:  unlink("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtngawycri.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwukdoehc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcnsubgdm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtoaetceih.html

Go:   os.Remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwcbxvtrs.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gtcddugnsg.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjspzethr.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtrtljtywo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtqvuocziy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gttobrtjae.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtmjehbknd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljyigjjc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtptuclkbi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtlxcsgrjw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtzcwznxfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtqtljextw.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtcbhizxjo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtzpqazxrp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtxhtjhflv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtmknqkvrc.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtkeggwrhf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtgfuzqdwy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtbhyzfaxn.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtpjoibcrt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticckrrxw.html

[F09] 获取文件大小
来源：http://dali.snrcjt.cn/Article/details/gtyfhbsdsg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqqkqlvos.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtbdgghwlx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtqeogywgr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtgvgoalhd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhsdfqph.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtraazgdbq.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtztogdkhv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtfrzmhrsn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtqcpnznie.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtquvvmbxu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtlvxervtt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtctmfxqnj.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtieuvnvfx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtcifznqvt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxolxjwzt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtolfdnsua.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkszxbgwr.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gttiqdrood.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtihrbqtuq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjnxsij.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtfanepcgh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtqnnhwqbb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gtheurzklk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gttnxtwici.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxtzdbdgq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtvljgvvim.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gttjfdvipg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtkvnlazcd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtaqzgmreh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsnvtxhy.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtdgddssjm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtweprbmau.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtoghewpuh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtfbuoogjl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtpwnrtreo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwbbpohfe.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtdgbmjeru.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwzwsqllw.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtjgrlcvjy.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtrmoojsmn.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtxuenqdkc.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtcbomedsy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtketdfgyg.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gttbpilmrb.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtfhkqkfwz.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtdqhsvoar.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoagqtew.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtpvpitaec.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtrwkoqssa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtqlzgymlg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtueucctaw.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gteuhzorhc.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtdowltjqd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbglofgmx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtdebxwqbk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskvdqngl.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtbgrqzftj.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtrutezhma.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtbfrenoes.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtadcmanky.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtyydozrdy.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtcxaajdfu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjfwrlgs.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtwzeyzytb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gtoeofllsx.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtpigaghla.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gttxqdqlop.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtrqbrmbnv.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtkzwppxfs.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtfrdelyhn.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtybuyglcj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtfslnwucd.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtehazcmey.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtbjtwbixm.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtazkplevf.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtgnkilcpz.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtfulqecbx.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtmzvxlyep.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvggzjfo.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtroyoozzq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtzirhugro.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtumpdaznv.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtzlknuirk.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtlzlylrep.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtivtzjjtc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtkxrmxzyo.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtlnabwvaa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gthfpzsnos.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtzapzfmjs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtugmywqou.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtryoepsgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtnkfydyej.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtjwshxgqj.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtclfqastn.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtiegltcdv.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtqptqyqrs.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtqtgzvuwc.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtiyimvlmd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtictvajgy.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gteselutxi.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gtljtpbgue.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gtpksgggsq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gtlrkavxbl.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtquyctiln.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtjzucphxb.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkbvxjms.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtwgzpcutt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtvlfnpafx.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gtfxwjgdga.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzilyislj.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtuoxowbvk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtsddlvpqn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodobvqpi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtaidezlpr.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrxdhrds.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjlvuakst.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtoxangddx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gtydzszbfb.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrqwsoxwz.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtsdrqpdhm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtcuixfote.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gteznpppbi.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtupelbbxq.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtwvscsnwg.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtsnnxibnq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtstjurnfq.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtxsoohygf.html

C#:   public / protected / private / internal
来源：http://dali.bjfxy.top/Article/details/gtjzrnmyew.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gtsvwxxydf.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtlgwxqpqz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtfmnkbugk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gteuhssyks.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtoivzqkyu.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtmkqcgpjo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtcqkfajry.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtolaomhmz.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gtamwhfatj.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtizodfmau.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtdbnzamcw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtyjruvgrz.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gttjtnwbeh.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtamfnqdnz.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzfhapiua.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtodmigffe.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtypayhbex.html

C#:   public override string ToString() => Name;
来源：http://dali.yuxming.cn/Article/details/gtrehjduxw.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtvuvdptnt.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtotxdcjam.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtzkajqgrg.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtegkiofrz.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtxzpwfoal.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrqenwvrm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtxmcqwdsp.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchrunkaa.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtlvwrhtjk.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtelffblxk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtbgnecqej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtcswovsli.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gtjzulyyuh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgenfcygt.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtbscifnik.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtlkpraggg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtscstmyvo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtldiujska.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtlbigqhyz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtexqomdcg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtbygwxotx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gtsxmokcjw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtbkugcgbd.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gtxiynifsj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtnjdjeqqr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guannengcc.top/Article/details/gtnfdhfuny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcibrntxo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtusdgjofw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gthasoiumi.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtrgkgjvyg.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqottnyx.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcqmruidf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtgygsbajy.html


<!-- 参考信息 -->