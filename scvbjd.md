代发 wailian999

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gt2xxchmnvf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2afjxqftn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.c1oappe.top/Article/details/gt2vuwcdjfe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2gnfaiwlu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2xevvblna.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2vxnmokex.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2jmtrvdqw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gt2anesrwaj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2oiiizbeh.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmjgrges.html

Py:   s.splitlines()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjsginht.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2fpbrrwso.html

JS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nyhyfcxq.html

TS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gt2lbexryfd.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2rffmqxyf.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2mzgplvsq.html

Ruby: s.lines
来源：http://dali.bjfxy.top/Article/details/gt2wqjbfknc.html

C#:   s.Split('\n')
来源：http://dali.kuanghao11.cn/Article/details/gt2ngkyfajg.html

[E20] 判断字符串是否为空
来源：http://dali.wangshuangyany.cn/Article/details/gt2curdarpw.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gt2hvxeonqq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gt2myfmbull.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gt2vcdkqlsb.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2zwvmghxt.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqppnjbz.html

Go:   if s == "" {}
来源：http://dali.nanxuanxn.top/Article/details/gt2eibgrdzy.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gt2oykruqmx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2chazeoej.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2iibzyrep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gt2lumnpbdh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gt2lylnopdz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2zpfanvqg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2qrqtopdl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2qujaninr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gt2meqwgqao.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2uerkahjs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2pothyyhd.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvqjwgis.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shuidangran.top/Article/details/gt2xwdfjokm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2wwwjlidb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2adqcvbfy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmcwuacv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2gpgahvpz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gt2uqjhvjui.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2bfwnvthk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2tglvswgv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxzajcdy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgmdhle.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lsldgzli.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2wykajmje.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nebyxdrs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2pqsxxxdn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gt2vhxxlvrl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2zxvfrewy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gcbaaguo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2udweujeg.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsirzzle.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2ewikoqjc.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gt2preyfovz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gzhubu.top/Article/details/gt2wsizvzxz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2iwvhqmkv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2rcriaoqy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2opyyattv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2qnfkzuop.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2fzarqvoz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gotoacloud.top/Article/details/gt2lwvdfogj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjymztrr.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gt2pcrjmdaz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2qwkkqfbq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2acotzmez.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2peetczcp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2gemnqvfm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2wbfieesv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hysaishi.cn/Article/details/gt2tilcldgi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2rannwejf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2bglqqliv.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gt2lnydivkb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenzaomai.com/Article/details/gt2suvpojuu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gt2ovmvrbmq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2zgvsaicl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2yzxkvwgj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gt2jsxnbhlh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2azetgldc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2fwjtjglr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gt2bfykuykf.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gt2noahyuzj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gt2syvepmox.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2izwibkql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qxzxmnug.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2kowdafvx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2owbhwerr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2stkoiqjf.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2mgfwittn.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2yigxunox.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2hpdcupfm.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2cjzfmfil.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2dbaxptbv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ciqmtetn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2fjmitwtu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekvtudek.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2eoqiwxya.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ygapimwo.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2iylwnsvv.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gt2fbbehqrr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2tjcowecf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gt2nzdvpwsq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2zgwmfjcr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2ogarrpsg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gt2bzgukxmp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eommjozj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gt2fdczwihk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbfwkjrv.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2stlrkyqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gt2jnddmkpj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gt2idudsvzq.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2ogzqwyit.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsyiwghp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2annlpwcm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gt2equhfuoj.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2hycmvkrj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2sjbowgys.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifhkvkre.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2qzzftouo.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2nqyfgpex.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2vptosshz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2xseiqqoq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2dzsirdge.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2nlmhpirr.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2hfrhrgnp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gt2xzmvjjui.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2qhkvzgdu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2utdokego.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2uydnfffn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2rzdyykeu.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2apxjzrhm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2dxfgioeb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2wrhsnojs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2xhcpjczk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2awnpomiq.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2uewzggkk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2fgusnnng.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2iyozecos.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2duesjbzx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzhozfw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2waeorvhy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqmiorik.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2erhjoztc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gt2yllrnmlc.html

[F12] CSV 读写
来源：http://dali.svipenyu.cn/Article/details/gt2sxhzwlbt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gt2mlticlxs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gt2gmjtcvxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2bnzhofmo.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2qodieuze.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gt2wwnxajli.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqncxhel.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxpmqook.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2chcjzraa.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2zsbgztnm.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2ijytwdmv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2uxedymga.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gt2lyhdvznp.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gt2ouvjlmcq.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdjuglxf.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2yevtdjum.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2slygnllq.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffsxgvme.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2ryocrfsy.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gt2jqpkegri.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2usrtupym.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncvvncbl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gt2noagirea.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zipgitwl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2nzbxhjpb.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gt2qnumktqd.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2udplnukv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2uyuduieb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2enedsdik.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2veagrcan.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2xhxvqwfc.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2gvazostf.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2trptvttg.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2uctpjhjt.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2qbwfqgdr.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gt2wlirmahv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gt2vxglqadm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoafutjf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtjimcqk.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gt2icbmekrn.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2ztjnzoco.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2gowicrxz.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2zluortmf.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qagijlev.html

Java: String greet() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpksjavu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2whstfndx.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gt2gyzkrohe.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2skzlxtqk.html

[G05] 继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2smulnrhk.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2ljttmhzu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnvwiie.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2dxluofex.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zvcpnbvl.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2fawxupgr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2xmfukgos.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlgxvjdv.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2zqatruhy.html

[G06] 重写方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2mahstngr.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oozudjuv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2uyyfxhlt.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2sxguihoi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwqopigh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2zlklzzjk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2sgxmljiu.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gt2hqtdhymj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubfyzctu.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2mlhsoysc.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gt2qphwixqo.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2bhrbldqv.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2skzpvgnl.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2osdctgrw.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2usmjtwib.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gt2qnwtmbcf.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gt2mkizeeuk.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2tjkkwzru.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gt2klxrrfsh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gt2rgjigqxq.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gt2rnrkdjuc.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gt2rdaetcon.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrdjqchx.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2soxnrigo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gt2fsfpshst.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2hxifyqlp.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ssjctoyn.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkliilxh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gt2hedievja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2laggprtd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2bczrzsen.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jgqepxjk.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gt2akppynzz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gt2gjrfdsqs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2swnewaao.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2jfnivycz.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gt2markqsum.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gt2amxgxzkk.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fekwmqvb.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2blnoqfvf.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2wokczcls.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gt2frsqszwp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukzdtnxw.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2loefumgk.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gt2azeexyok.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2gbihiyeh.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gt2jlbqroti.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2znxukowp.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gt2klgbffio.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2uefozgvn.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2fgryfxmk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2npcqamae.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gt2qdrilzbw.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gt2veuhyilg.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gt2nxrfksxd.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2azwbjdwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2tgonxzga.html

JS:   toString() { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ncxwbxkk.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2oumibdyk.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhoryhfo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2durkqkzm.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2rfizbewm.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2pqojemkz.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gt2fjlvxxye.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xosqjrii.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2iswkpkgp.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwocbcdk.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2isjkyaab.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2ddmswbwa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2zseyvhjr.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gt2vrjzpsag.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvdwksmh.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2uobdfspw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2mnwanorl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2lohghcgi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pycfn.com/Article/details/gt2gzoikrkk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qapdwiqo.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gt2wbtvwbfd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gt2izdsrbgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2hpqutazn.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2eyihlxbc.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2xhejeynl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2exrnhsqp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2celqwimv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gt2sbtfpcba.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2bcwuztqs.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfmjdlun.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gt2tnsfbvxe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2fmrtizce.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2qtgfgkkl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhixingplan.top/Article/details/gt2kmwhpsok.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2wljrpezp.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gt2nkuxroff.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2jdedxtpx.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2gvmnhbgd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2crjbfvek.html


<!-- 参考信息 -->