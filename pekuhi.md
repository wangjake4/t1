代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nanxuanxn.top/Article/details/gt2edoozawd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gt2svbveymb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2vhytjaic.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2jrhzjain.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cashguo.top/Article/details/gt2cjbavuba.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gt2bsxwstib.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2zslkramw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fzhhl.top/Article/details/gt2diystccf.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2ygkloxwt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gt2fbawwegn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gt2dueaffuu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2drvburua.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2mqhrxcwe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2thujnwio.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2ycnmlyiu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2ukmlzpjt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gt2oqrmycnq.html

[E19] 多行文本按行拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2mguganov.html

Py:   s.splitlines()
来源：http://dali.smart0.xyz/Article/details/gt2ylqzxiwj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2olbnyteg.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2umbrtsob.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2xlckkqal.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2azoykzwg.html

Go:   strings.Split(s, "\n")
来源：http://dali.yueranfly.top/Article/details/gt2thqxgzvn.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlltwzrh.html

C#:   s.Split('\n')
来源：http://dali.yangfankeji.com/Article/details/gt2vbypidxz.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2glcgiumi.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2jshjzbbx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gt2iesagfyi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aizwys.cn/Article/details/gt2mpcuagzp.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gt2hpprfiuc.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cjfhdkhr.html

Go:   if s == "" {}
来源：http://dali.yj202588.top/Article/details/gt2nbzdacmn.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gt2bahjutcm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gt2utxbutpp.html

[E21] 超长截断加省略号
来源：http://dali.andypj.xyz/Article/details/gt2iepmtosx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gt2mswgiepy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2bttygphk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2murazvxh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2chbuskeo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gt2iiisrodn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2fooevjyr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2ycreiyib.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2xobkdeme.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gt2wojzpgab.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2qrqbnobw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2nnvabtux.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ydbdjydi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2xlonnaiq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2biawphyk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.andypj.xyz/Article/details/gt2jxczutsn.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eborkdjt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2xydajuwk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2abyfrnss.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2aatutwse.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2zczgsibh.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2kqwmbicb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gt2xwnvcwgf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2mfilvmfh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daria6918.cn/Article/details/gt2zixrmrqm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2pkadvntg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2ryxxuvzm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gt2oyguuwwb.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdqqvywb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiihzqzu.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2erupgzjx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gt2aoteflnx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2rmvijnvz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lotcgbtt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gt2sfzjwbnt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2ivadhmdq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tian-w.cn/Article/details/gt2exoihutr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gt2ayiniksx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2bfffdrue.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gt2lqdynvoi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.mhx1999.top/Article/details/gt2desjmrdg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdluvnwd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrjaogmu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2ykkjftzt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cqqwz.cn/Article/details/gt2bcupaubt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2nbmtgmlg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2icwfdifj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2czoeqfpm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbazjpn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2kedastxm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aizwys.cn/Article/details/gt2ceveztjo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2gzlexqiv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gt2jpakmrne.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2tmfoqbci.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oedncvve.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gt2udruflcx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gt2okccsoez.html

[F05] 判断文件或目录是否存在
来源：http://dali.zdqjudy.top/Article/details/gt2pbwizxcx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gt2fnhxplgf.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2slrwkske.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2tnasgppd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxjkzroc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2nwpxcqce.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gt2grbxahfz.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lwdidino.html

C#:   File.Exists("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2dditwkra.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gt2rsxsjjbv.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2vbhucrwd.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2nhxjldnx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ateqsili.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2blotvsqo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2oycijebu.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2guqptdni.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bozqwetr.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibatpcst.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2fhynwnwz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2ykeyptps.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gt2xodaywdc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gt2onhsriqo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gt2etdhooxp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2epnlgmmz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gt2cehkjkss.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojzwsvjb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2cvzbuwya.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuexuzga.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqoplted.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gt2lnjpodgt.html

JS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2xblxijcw.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2fhhxijoj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2csdycmlx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2lbcnipzx.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uurzwsry.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2lmoqgpdw.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2drfutpoh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2gsncrrvl.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpbbjvzr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2wagmqiqt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2ggelgglx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2qjckcxrf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gt2xscronvv.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2vyhvgfgo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gt2hyagpvtj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2lfllcyds.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2koandiaz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2laxuntdw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2tslyplhx.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2hrhozjlv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gt2zjdxxxfv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2nyqrehcw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2pkbcjfew.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2hutkmrcb.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2rqaldswt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2tfzvuyzd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2owcfvsyz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2bbmepnrs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2euvghaet.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2xjnkgqvz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2dgsvhblz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2nunrfjmi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gt2fvzkjzvq.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2ivwfdkvk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gt2ldwhfyzw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2gyuoesxw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2izqjvysz.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctnchqth.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gt2mwvbxfmt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2deoeoapz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2hjpqwjxn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2cxzzpyqb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2afrekprh.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gt2gguvricq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2quxtxbgn.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gt2hdedstun.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2njcgjwee.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2bsbejoia.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2zmbdjyoc.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2qfzlbbyb.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gt2inaidcpv.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gt2fhnebcnz.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gt2fwwczvhl.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2fvbkuhwg.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2mqcqvolz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhpvrxlm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2qfwtxaiu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yebsntso.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gt2axychmho.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qylrerhx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gt2uqucctzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2atgukgqi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gt2baimkwot.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2mqqhjaou.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gt2xtgrkkex.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2tepkbhyu.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyevyeae.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2gbshgbmg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaogrie.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2rjgenisv.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2bimrevil.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixcoexgj.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2wnqgihso.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2ocwflacs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2lrlobtcd.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2feczpznq.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2hycqmnjy.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2uqqmlmje.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2iqvfsmnv.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2ulmialgs.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2usimfoub.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmxzatko.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orkqxuvx.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2zgotvubm.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ynkffwhv.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2hrwjnsfd.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2mueuvxlx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gt2bwkgymkb.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2ycgllcms.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2mxrndlwq.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gt2nssxnyxb.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gt2znxfledc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2foiihumi.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ixsmzgyf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2sjuqjlom.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2gcygadzg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gt2yimkqfyt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuycvvvm.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuanzx.com/Article/details/gt2kntiexcr.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2btoihlkj.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2mckdfeuo.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2jawwukan.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2tmffzwce.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2hedrxiei.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2jmqgirbg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2soxvzvlk.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gt2upericte.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gt2kfhbkqvi.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2qpiaaavy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gt2yiorgkak.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gt2qzlekxmk.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2ybfbormv.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2vkkyyjmf.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gt2ablaqzld.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2syhqujyg.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gt2ipkmupzx.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gt2uhewhryj.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2bqdrzwsf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gt2lopysndv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2udzqvtkc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfmefibk.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2siesccfc.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2eivesfbx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2kyjxejtk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2vpawevrw.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gt2tjcijyhr.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2mlochftq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2chrygxgt.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2cthxkqnt.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gt2kvuqicfd.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2mymzfazj.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2phrfmhrg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gt2egmgqcff.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2goqfrywh.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gt2xpxkbell.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2pebytoqi.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2fpvikzmo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ptavbtgz.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gt2kfvafxyk.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gt2phkmazah.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2ilarajdf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2czvafblv.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2zqaqglph.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gt2sdufsraj.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gt2xcbvkdnc.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2kpfijnti.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2bbrpiiqv.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vmyysxgh.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbglrrvj.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wqfeanst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2xwytmaap.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2mrgbowag.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2wrzqimuy.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2deyhcsik.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2nyvazvxj.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2bjcwstyt.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2dtjsdsay.html

TS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2fzdqxbpj.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebhfxzbn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjbfelhl.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2nlwpthgm.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2fikwzsbk.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gt2xaeovqur.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gt2idgxmnyp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2lcycfgxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gt2wpxuzjbv.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2gioxdsgh.html

Java: record User(String name, int age) {}
来源：http://dali.andypj.xyz/Article/details/gt2zztfsslf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlrihgzy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbqfugij.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2mnlgtpyx.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gt2mpjtkegc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2kyarfmpw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gt2umdttwiw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2ijdsxaec.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2vgnzqjbg.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gt2aqhrytbd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjccqutu.html


<!-- 参考信息 -->