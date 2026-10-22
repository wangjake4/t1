代发 wailian999

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gt2psgwlcyw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gt2tievezdv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gt2tcnpskiu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2uwtxeosj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2axmkocog.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2unnezmya.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2alucmlyd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2blkepwah.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hysaishi.cn/Article/details/gt2nonzkxaq.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkftzvkc.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gt2wvvylivt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2apdxchxc.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2buhfevho.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhwsnwbt.html

Java: s.lines().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2bbxcurip.html

Go:   strings.Split(s, "\n")
来源：http://dali.aibaodan.cn/Article/details/gt2neowqllf.html

Ruby: s.lines
来源：http://dali.tianlin.xyz/Article/details/gt2nzssqbwi.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gt2qbufhmda.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gt2ernaxzvk.html

Py:   if not s:
来源：http://dali.jqgufenzy.top/Article/details/gt2fktaeoow.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2cztvgqkn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sysykeji.top/Article/details/gt2pdyuczdz.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzqsreik.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ovwvyiaa.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gt2hxbmzmni.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2cvrpultu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2vizoupcy.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gt2ldatypwx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yonumen.top/Article/details/gt2ptsaxhrf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ratbzxyo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2rlnokoei.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnkguftl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2zzntytrq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gt2ajgqoqbh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2rrnsgdgm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2xmxqrxec.html

[E22] 字节长度与字符长度
来源：http://dali.iojbl.cn/Article/details/gt2chwxeflj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gt2onmtwscb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2bcptenwk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2mpdhkvcn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2xbmsurtx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfkhwaqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gt2sskmvqxu.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gt2nwvfvpbn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcijqpcv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2luojjukr.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2etgyyoso.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouuyfypl.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gt2cmwdvlqz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuxming.cn/Article/details/gt2dsigebqg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2qjxlyqog.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gt2blfrgqhr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jskgzkgm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ppmmuzjo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gt2inrqikyx.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2snevscar.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2affqmcdg.html

[F02] 逐行读取文件
来源：http://dali.hnxiangtu.top/Article/details/gt2mqavrlyc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpqozzep.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenlongwang.top/Article/details/gt2xdzalgcu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2phuhmtqo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2uoarpsoq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2ahaexogv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuozlhdv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flgnhsox.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2jjrqlwiu.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gt2ujcqjghu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gogol.net.cn/Article/details/gt2resqwshx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2ymlrwyuk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2afityrfz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2prscgzsw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gt2fznyhiki.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gt2bnnbrlge.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ppjwa.cn/Article/details/gt2dkqgyhrv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2ohqobaxa.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2rvxeooqn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2xxdbrjyc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gt2sktfvidq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2rdqfgboe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2vtjbpxtk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gt2apietryv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2zewbwtel.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gt2zkquolhz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gt2jgednzfm.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbyiyatw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2moswfjdw.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2mqqyatxg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2lpiqceny.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2igtasyly.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2urpnvadk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2cyibxzbg.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2cngcanbm.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2rylvipas.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gt2xdksuzta.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2nyimgxqo.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2sgjkhdzi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2twijpgba.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2mafwpcqo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2tolaogmg.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcngfhly.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahgxosmd.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2drvskron.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2zskrnxku.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gt2nivtehny.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2ndjwogms.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2sydqmoby.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2coqlftmi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gt2rcpffmfg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmxvtpuv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gt2rfplbfdy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gt2otldvala.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2swwduhwb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gt2psepslkp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2apylvaxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2pzklrgjg.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2rbwzvfjd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2nknbeyhd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wydozwto.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2uffsbafo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2nbfygnfz.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gt2dtdhzftg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2lokrvdgo.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2vfolrqtx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2wqghwpwq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gt2rrogqtam.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2hyrjuusq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gt2qsuvgbxp.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2kbokmnhm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2vjydhumq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gt2ghtqypww.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmiweczj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2ahgmwazn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ibpsbivi.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2pqghmyvq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2prhqhchw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vwqpuqdr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wswblaxs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfpybxpk.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2hjkuhazh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tccngiir.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvnzutel.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iepykzoy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2izgabvnq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsjytpfc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2kzkfaphn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2sskdgqje.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gt2yhwyxicg.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2urdcjgtx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2yfqsdoqm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gt2ibazdblx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2hlrhlrjk.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2iujuyexq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2tjnqffox.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2dfiskvbd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2gosglyvn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdblgaol.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2xohmcjnp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2axjujhzl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rhkxndxq.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2gtkgumfx.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2okcgfxfb.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gt2jtvujyqw.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2pxtzjlic.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2wkwclfog.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2luuffnbd.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gt2zhfvoroy.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2bgobgzbo.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmzioezq.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxqvoedh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2rhoiyogp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2kthgxkgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gt2ytnrqqcc.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bqdpxgix.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rcyvcwex.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gt2qfryforo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2bjrqwube.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2ugcyihbv.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2ijoafsaz.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2hekiqfzx.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2faxnunyd.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2ytsblbtb.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2dyanlxch.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2notzpjbb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2lmnjkbcb.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2ruzamvpk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2xrhvizcm.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2voweufeo.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2zyqgospr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2wedwctxo.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2cdnouhnf.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2gwxabzfy.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2ydhiqfup.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2usguwsbu.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2zzxsjwzy.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2tnfqcudy.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gt2mpnhaywb.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gt2ramlhuxv.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2scwcigyy.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2jceqizew.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2nfjsttpz.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ihdmesfa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2pdnpljcp.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2rtbshqgr.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gt2syycfdxu.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmtrwubf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzetjvax.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2gyzfvatq.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2ytavqgbb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2granalco.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2awauhjoj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gt2iohkrtov.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwcqqrjv.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gt2dtfrwycz.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2hxjuejat.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2xhsyxozj.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2usduegex.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2cidehoyt.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2blwimnnb.html

Java: super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2mrypvllt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2zaknocke.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2xvnyrwol.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2ozrsvngo.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2fcblehxp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gt2eldnulyb.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2edjtzbrm.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gt2llbyoliv.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gt2hgcexgml.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2auvyjyve.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2liaxuldx.html

Ruby: def self.f; end
来源：http://dali.sweek.top/Article/details/gt2gffvxsgm.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qmdupwlg.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2hezlmhzr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2vqyxbhig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2xzwwlfbp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gt2dxsvpwrt.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wplkpgyn.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ftsracac.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gt2ursifwbs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gt2jyffcgep.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2mrphlvbw.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gt2pfchcqnz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvjwqkul.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlaoescy.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2sseusuls.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2hiosrktq.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2pklpftyd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2ljbanbiy.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2gvpbkuej.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gt2aaciwjxt.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2rpmpmcae.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohnvkeek.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2phtzgsir.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2tvtexlsp.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2shhlotcg.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2destjudw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2qzdbzrfr.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2nxikadav.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tgsegtkn.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2beodkjdf.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqcxwjtr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2zdsqqbeu.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2euqmqbni.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2vyjqguip.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2lgplghps.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2izxayzec.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2qljpjtcu.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2qaiwxfzl.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2xszqlkbl.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2xuzftyed.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2ltgbsvcd.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2kassrjtc.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2eubymmyb.html

Java: u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2aljpcaok.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yanxiufei.cn/Article/details/gt2rgaowuuf.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2gbkjlgfl.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqhuhqnb.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyzdqekm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2omjwlddd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gt2apvkfxrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gt2wtdsnprf.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gt2zdzeuiau.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2dzvwmehz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258.top/Article/details/gt2affasduy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gt2stpkgupg.html

C#:   record User(string Name, int Age);
来源：http://dali.sweek.top/Article/details/gt2zufekriu.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2yhnkxaut.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gt2hfljraeq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2hbqxpqmn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2ziriuyzi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2smadyvtt.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gt2qdcgcrae.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.svipenyu.cn/Article/details/gt2wsiaxsfd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whbyirwc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2vzjtxpkf.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gt2hitvdmtw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2gpdzustd.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2hgmyibxn.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qyimkzzc.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2vgfjrlzm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgkpimap.html


<!-- 参考信息 -->