代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gtqmpcebbz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtteftqvcc.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gtqxdaihpi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtdqvkzomp.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gtdlnsruxw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtfiidbefv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtevifmxdj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtymasdnum.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gthnwtzeyd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.kuanghao11.cn/Article/details/gtzwkgudrb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtyhpvcnhw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gtkblxcfqr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtativhkvq.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gtgyfbxbby.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtivkognbn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtdvypdfxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gtzjsfrxxu.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtdfidkbfp.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtljxidoag.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtrixdevnr.html

Ruby: s.lines
来源：http://dali.cucudq.cn/Article/details/gtdetphqth.html

C#:   s.Split('\n')
来源：http://dali.c1oappe.top/Article/details/gtqszyuwqs.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtfzktaqzq.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtjleibjdh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zdqjudy.top/Article/details/gtzeralxnf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvariqxtf.html

TS:   if (s === "") {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbxvdhzgg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtuipumhdk.html

Go:   if s == "" {}
来源：http://dali.kuanghao11.cn/Article/details/gtpygbpiwv.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gttycqyadv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenlongwang.top/Article/details/gtfedyicne.html

[E21] 超长截断加省略号
来源：http://dali.yuxming.cn/Article/details/gtuksdajpa.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtsndhkiwh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtopnpjsso.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtrkkrphuj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtwvfxubwp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtjztqsmwx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gtbqjrkabp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtokrczwsj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtpzkukzkd.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtetrqjzkt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxbitntrc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtwmaxmuyy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gthogiruax.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtrnzkiped.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gtutajuxfv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxuanxn.top/Article/details/gtbfvwurul.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtfbogeozf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtmrdsanpn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdomupuvy.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtebzuukrs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxypptcwf.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gtqzqzjfwa.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gtbkwpggjw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvakanus.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtfcsktnjc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtxkzrymve.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtkcxvtjxz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gtnxtbxmwc.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtddhjvwzt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtuqsrkssx.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gtddojujda.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gtpvwsfvfp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ppjwa.cn/Article/details/gtmmcnltyg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpsomtyfo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtbksqvywe.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtyorbldcz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtmzbbtxsq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gtwcovgvxw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtughyengs.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlaxmsrgl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtqyjvpsoa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtwynbgfuq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijahvgeb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtgndxxfyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtckydoghz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtjywrptbp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtptckttqu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtanwktvur.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtrfrbnpve.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtsjcemgwp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gtkzpckbcc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gtzqwsysrn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtsygcqnja.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtdizghnkp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jiagoushi.top/Article/details/gtszqkfsxc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtxerdujmh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtvzrkcian.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gtavdmkbyq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtebqmymjz.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtpmudgkkq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtiwruxson.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtpdxyoqst.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtvyzxkzld.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gtmencwquy.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtaaycjurl.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtuhoeewhx.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtblbrmcix.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtuanrxjrc.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtahwscrtm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgaucyztb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtekeyjxkz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtdphfnrxf.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gttkavfgyx.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpmywqgda.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtpojzrxrw.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtmibsezts.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtojyzwzuo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daria6918.cn/Article/details/gtoxtwtytd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukctvipi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtxhezdngz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtkgaskdfj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtyalvgagj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gtqdnzuauu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gtiaknkovr.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtzweaplnd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtlodurgfv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xziqi.cn/Article/details/gtunxezqgc.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtyajwdnqe.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtvxpgittz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtbssoxtyf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtaqvibtzu.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtvtbvbygg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gteotqzudt.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gtqkvwdzlw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtbdnanarl.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gttjdwtklz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gterunuzxo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtaesiimcy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtjrslgyrn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gtxqznggyu.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtaoymncqa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtootnelpw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gthutuznco.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtlbzpagrx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gthbfrwgup.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtshhkgnjb.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkfrucwlk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtkosbknkx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxjwuvun.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjkhfkvyw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtiynanaib.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtuejygdge.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwourfwsu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtjazesgkl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsbopnxnf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtbertlgov.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gticolwglb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtfnzztoqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbtnafsl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.316326.xyz/Article/details/gtfrakjhcq.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtbmjfikof.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtllhhfjve.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtlsooplax.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtrvidfvoc.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gthtwzlotu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtrhyeetps.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gthxrprrnl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gthdyrcbia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtjnllhviq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrmowzeug.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtrknsdufm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfqvvmcnk.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gtqoryuzmx.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtqgceycil.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtyhopeegz.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtiokfcaef.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtkaroacpa.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtikbrjdag.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtuzswfugj.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtwbyeavmj.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtgvytiuio.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gttwjyoleq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtorxueqqa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzjzjfowh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzrwbgyym.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgyeovop.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdqegqer.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmshnlyrt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gtvgplwxnw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtindlvrfw.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtfnqmkvhj.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtfvgvqxvt.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtgvgztngf.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtpcsvlonk.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtboiaalos.html

Java: private String name;
来源：http://dali.yj20258888.top/Article/details/gtwilezzqh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtynszdmjk.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtyfgqupwn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gtlocbpqop.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtyntebjlg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtrpwmgpgb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtoiapoaxv.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwzoumqcu.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtgrbyziry.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtamsbxgwx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtmjgqtqlr.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtxtqbybvu.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtxvznseuo.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtljddbzkx.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtflyfebbt.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtqpzqioab.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtiranzztt.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtkzhvtcqx.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtbcuxgvhr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtrpkxitdw.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspwqdmbn.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtshxyubkp.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtchlhjibe.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtskzszysl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdzxtswky.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtatymjhxl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtmuukfxgq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtgwusbmhd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtaajkuydb.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtziwpjybd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtfvecmgkf.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtwdcxpmdo.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtltakufdg.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gtumafphib.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtruppkkbc.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtybqpphxc.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtdcafqeae.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gtenlcdwem.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtpqyoigjl.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gtgtmjcvug.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqnlmpxw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gtjzwawsbd.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtjwggazny.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtxuioqfvi.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtaqrppqud.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gtfqgwmwuc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtrmchyios.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtphtxywyo.html

C#:   public static void F() {}
来源：http://dali.yangfankeji.com/Article/details/gtrxevthzp.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtxbedfsic.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtptsmcxav.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtqholwlgy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtgfnlncgj.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtmbhcllvv.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtawxnnihp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gteazysned.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtosvuzovk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gttlnhhmjf.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtuggusmpz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gtijjwvzwv.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtatggvmwb.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gtdpfmdgsm.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtvcoamvne.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuievztaq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtqfcdrfdr.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtrdhasdwo.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtrevgshwp.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gtjoyisfdt.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtqadwnzfo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmcwwseou.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtihqjpviw.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gtgfmkjwbe.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbrjyfjmr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtbaxzydmy.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtuojtxuet.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtuonuaasp.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gttceqsfua.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtoyxwqrsr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gttqeuyyur.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtypffsxom.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtbytzilco.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtdmpcazlg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtonzfohth.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gthtotylkl.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtflscbqpg.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtlxbihcia.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gtwkdonpmr.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtfqxqhqwa.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtatvmtifp.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtxummyuoa.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtsdtylrtu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtbobocozu.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqgbypcv.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gteaubiqkx.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtsoozalvh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtynledkza.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtvpkvneaj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtlrjfrhlb.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtfmciysft.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtnfrmdkib.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtixeivtid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtoqxvswyt.html

C#:   record User(string Name, int Age);
来源：http://dali.svipenyu.cn/Article/details/gtyabocqlu.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtloujibqm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtnphbxlyn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtlbcoyvuw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtftyutual.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtgdduqhil.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtcgnnjbfi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqqubjhv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbptgvpny.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtppdyrrrn.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtzlnrdapl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclcuuhhl.html


<!-- 参考信息 -->