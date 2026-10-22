代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2nksgnhqu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gt2vgkhbbgy.html

Ruby: s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ctlqwkss.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gt2ugckiina.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2raxovgfm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gt2dbidpafh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gt2smdffuxk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gt2twcaeduh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2vfvybyvn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2qqtvaefn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zlcikjnp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2zwqodbzs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gt2idagyxua.html

[E19] 多行文本按行拆分
来源：http://dali.haohaochexian.top/Article/details/gt2csirrcpj.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gt2buomacuo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yvedp.cn/Article/details/gt2ajylzvml.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gt2vtdllnmw.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gt2lmvqzwep.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gt2rjrkndmd.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gt2hrbhrgny.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gt2wbjgsawa.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gt2wbdmwvuy.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gt2ijpkhapv.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2pyhpdqcp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gt2zxbelwnc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gt2coloreqi.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2tdbjgzpp.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2cmaqxbxn.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gt2czbbolkv.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gt2veemqpbl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ofllnevk.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncekmquj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gt2ufatdrqw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqntbsak.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2oubdjvmb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2gisqiyjb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2zeromzbg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyoxqcow.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rttoepnz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gt2dmgbeaga.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2qptlmvvn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2pjsmgkch.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2lsczrtze.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gt2ktvdvwre.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2wtxnbzvi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2bhbxhyvh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tian-w.cn/Article/details/gt2ggdbdluv.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2fdbqmwcg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gt2wunkowxs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2qjinigsa.html

F. 文件与目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhtncsbc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2uwskrmtk.html

[F01] 读取整个文件
来源：http://dali.andypj.xyz/Article/details/gt2qjusufgo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.kuanghao11.cn/Article/details/gt2lmcajvzn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2xldvggrf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gt2pykoewqi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2hxtvysmj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ogxximde.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2qazijfui.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2nrquisxp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2mqjuulsi.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gt2cemogrlc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gt2rynwlsqh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2afewiopu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xgzutenx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gt2jatmjtpi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2ydedehos.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2zplhxsvj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gt2anqfviws.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gt2bthhaqyg.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gt2otsoounm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kaeeanxf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2kyzojvjn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhsvsvm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2ybuaxzan.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2krwppken.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2pbydcuto.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbsjccoe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2obqwtwzo.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gt2kuowbxyv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2erbnbeze.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2lapdlvja.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2hgchiwxt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gt2qkatwoxn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dkdeeypz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2poyeqcoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2spmsgmhq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clryduyd.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2fpzullxy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2aixmpgji.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2ndhtwxtu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kcrcxdtc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wovzfxkl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2hasntppc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gt2mvdchxhs.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2gxewfory.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ibsqlywi.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gt2squvbtcd.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2gjewedzg.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2buodzufe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2offkscdo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2uzzgxlqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2bloxhyqf.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2osvotlqu.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2xcfowzgl.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2dtrjaxqs.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2nijmejbt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2kgyuwpcv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2smcyvktf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2uzmgouxa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2knjdvlnr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gt2qcseibil.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gt2jbgcxkmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2hsrolfqf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdqbbyab.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gt2pjdjtedz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gt2uvhvjdoi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gt2kghpqxzi.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2drnjjebk.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2nvrevume.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2altbuitq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gt2llmubkoz.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qyvpxwyb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2azxkkkjy.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2udkijwti.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ujilrrzp.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2krsiixwg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2jocksbol.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwrxvbgq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2qbxumata.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2hgngvznr.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2duxjaqos.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2ygknypem.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2cluhjcdn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2khtswjfq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlrxnpr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2ugjuoafl.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2bktfvcfh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2coseuewj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oznzohvf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2igncasrg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2bgaenvvl.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gt2dkvtlauj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jppuquxx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gt2riuifmtq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2gmpwtxlx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2glfpmzns.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2kvrdljgf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2vgxbaycl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2zagnojdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2lymgzbmd.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdcustcc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gt2jghbzfit.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrgzyipa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gt2rnubhkbd.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2vuqkfoli.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2flezcktt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gt2xscbebnz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gt2fvyjlpdt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gt2gqpwzxcf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2usglbqkp.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2nxuqjdsb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vbghglai.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2oiialadb.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndxbcgsd.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2fqptbnss.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2ngjwdyoz.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2lftqvmdh.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2cxbdgftb.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2uddmargh.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gt2nrliptii.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2omkziqyy.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gt2vtrlyhgq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2fddlxtam.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zycfv.cn/Article/details/gt2wkjietzy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2zvhzolpt.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2imaeydum.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2hbwvyidl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gt2aeissred.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2jegwgnep.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2yblpnlhh.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gt2glpuohxz.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2twzyhtby.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gt2qerswnng.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjlddbve.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2jsgxnvik.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gt2pvusqtww.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gt2ebygcwuj.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2iqtfzcmp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2npxtkmcq.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2zxxnxjyg.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2szysrxpc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2wkslhzfq.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ynqwqafk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2hwxqclmu.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jewhotnl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2stkapfmn.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzacnevx.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2lbovmksp.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2qjmulvps.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2seflrbdf.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2hlrfngvy.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnogmqqx.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2xilgyesb.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2tawsuxlv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2dmkdmhiy.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2hwxgmlgm.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbmwyxqe.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2eqmwuumj.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gt2rxunmumi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkrxeuxd.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2tdrhcark.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2kbdkzjwj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2vsqjuvrc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2frdbivth.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2naeoswwm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gt2mkczypdc.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojbroaha.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2tyipnfbe.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2wyoolesf.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2fwzknway.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2xpbqbgcw.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2jherljio.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gt2fqooxuyb.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gt2wyotkhgo.html

C#:   base.Greet();
来源：http://dali.dashuyun.cn/Article/details/gt2hjeejpfw.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2zjsfuinl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2zdkhvnal.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2zroeyzmo.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2prqvjdug.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gt2kyqfouwr.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2vayplkax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2dlhvhucg.html

Ruby: def self.f; end
来源：http://dali.jianghu66.top/Article/details/gt2wrnebtyq.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvboncmy.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gt2qwceumfu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gt2jeuxbopb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gt2tiakjzbx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gt2rpuetsxr.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2xgxbfskg.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gt2syfyqedt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2klsdpkmr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gt2hollxiey.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2sbeccmdu.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gt2aruwchat.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2skyveubd.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2cdqtxois.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gt2wplntzde.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2kehoxypx.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gt2flwgamuj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gt2aytnzula.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2hesboiqv.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvolyrub.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2octyjxhi.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gt2bsfhqceg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mfdxwjet.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhlaqxux.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2aopjcelq.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2ogcqdoho.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2qwvzsrhd.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2sbfalguk.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftemajqx.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gt2nfeoljlu.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2jcsmkygb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2jbczzzpi.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbigldvy.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2grttazym.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2drfwptmv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2qnoldbwd.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2kitdubxb.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2jjxnfxiv.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gt2ogkvcsan.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2nqkiargo.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2xzckhjrf.html

JS:   u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2tteqpcmh.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2oaeuwubb.html

Java: u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdjtdabu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gt2sgclducz.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2vxattudg.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2yrysdwam.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2swajezhn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gt2gtpqjjqz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gt2uhcjzxja.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2ezgkvwja.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gt2vopzbffi.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gt2zftwljge.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2miwhpxpu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2ocawnhac.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gt2smxkmyco.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gt2uzdjpmtf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2ovrbnwzm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zojpdtzo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2doioxywu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gt2awmxtink.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gt2dusqqnyy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2ueksenen.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sufxvd.cn/Article/details/gt2bibwwuml.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzxdohzw.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gt2famjngnr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2ggjkqqmj.html


<!-- 参考信息 -->