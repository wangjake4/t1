代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gt2fqcsvjwa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lniimhbm.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2jghhnnly.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gt2zyhpdwmu.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gt2ryumoqwb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2dbyggvmt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gt2mpqhcvna.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2wweoegqg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2xkkvpcmo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2nnlwicdh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gt2hzhupjkn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gt2zvajvxyq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gt2ppewdxir.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gt2gfjnmmhg.html

Py:   s.splitlines()
来源：http://dali.haohaochexian.top/Article/details/gt2nqissknc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2djfcnzit.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2owelbyza.html

TS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gt2xeqipywq.html

Java: s.lines().toList()
来源：http://dali.wangdashe.top/Article/details/gt2xynzfvou.html

Go:   strings.Split(s, "\n")
来源：http://dali.dashuyun.cn/Article/details/gt2cocaewaa.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2lrkysxgd.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlezxjvf.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gt2easqydal.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gt2izwjgoxn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gt2mastsrts.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.dashuyun.cn/Article/details/gt2htlhursv.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2lcyekhbk.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2mqcqowzj.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gt2vgtfwojd.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zfjlgrui.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.smart0.xyz/Article/details/gt2vvjaqroj.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gt2bhtouzso.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gt2fevdasta.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmtqaved.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2aqsoeeve.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2jmrkbzaj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2huvtcjax.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2iezndyqu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2erpjjkim.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgmbnevk.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2xchbhaok.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gt2omdrtibd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2vczckqan.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2ftmbmvnh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2yrrvntze.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2spcgviko.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.smart0.xyz/Article/details/gt2xyhsieja.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2bqpvvups.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2hppzdjuk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ybbjmbvx.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnipdjvg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ikocxzyi.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gt2nbvokjil.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2aaequray.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2amkehivs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.nwbrower.top/Article/details/gt2dwlddrno.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gt2lbqfsblz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2xnkuqmhl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigufen.top/Article/details/gt2imsbjrhm.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2tqakaccd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2yjvjtjww.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2dkgadgcr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gt2ngrmwawf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2qjwzqcvn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nyrjzild.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gt2gxgvficb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2meuamcja.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gt2lcwcunve.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brxarcaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2vspvtvqi.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gt2pegafqvh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2giwmiifr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2waumujim.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2abwfezwf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2cxdueiai.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2zdizvsnm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gt2ulxbmkis.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2rfbppfsz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2kiibezbh.html

[F04] 追加写入文件
来源：http://dali.xuanzx.com/Article/details/gt2nqamvuou.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2ewxxgpim.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gt2bqrgmxbt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2gwphnruw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2ehogrxbd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gt2smnnwmbn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2dneyxscy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2raruyfcj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2fwmfzklu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gt2nxrxnufm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgsoovyv.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2yckfmwzk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ykpmvwnv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2yodelhtg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2rweuvgto.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gt2dpjthxca.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2iuviqcex.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2szpwzytb.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptejoqli.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2nearcavy.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2yhobyfrc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2bjjvtxsr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xggmmlsk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2lrzrzxvy.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2sshycasg.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2rrjevshp.html

C#:   File.Delete("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2pnsgyehc.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shckljpz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2ofjurveu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gt2qmrmzwnq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2jypybfym.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2zqldjapl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2vfcyvrys.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gt2plalqocz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2qorhfebu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gt2iywzcdhm.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2egfzsjbx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gt2fgmwbmxl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bkbqyfej.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2rwoiidyn.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2gnysklex.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2wyrxqlkh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2thrhlzay.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2piebefto.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2dbtbxrrg.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2zafztcsn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2uiimruhq.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2gvajmvgo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2ovjaxabi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2xsurfzyz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2ohharnar.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.vqdsnc.cn/Article/details/gt2ubsjwjmz.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2kxtuwgts.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2hebbywcy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hfpthk.cn/Article/details/gt2isbiltnc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2snyzxpdu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2bwctkthe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2ppyjwgam.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2yjeoigkb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gt2wgltfcpd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mjqtutxk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xbzrpevq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2uiwspuur.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2fwdjrgdc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2znupatgt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2qfttlrod.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zffcripo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2pgxeqpks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2cbglknmy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2farunofz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zzovmdvm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gt2xzcxduwc.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2sqlkykdb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2argbdwtm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2caofmqty.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2hpksncqp.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2gzfwlvmd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gt2lnvszvdx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gt2gehqzswp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zclwnfbq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gt2efjrnegf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fkgwrmnh.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2npgzzerd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2umgeyeoq.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmwzeqed.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2nbbmrjog.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2aikmhluz.html

JS:   class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ksxeeize.html

TS:   class User { name: string = ""; }
来源：http://dali.9152youxi.cn/Article/details/gt2otipstud.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2sgzgyipt.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2uazxoots.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2oswlwroo.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtlufytr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uogiesfm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlfhsczy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gt2bdrgpdzu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2asyhmqjh.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ufnvkbnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ecbgxrxd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2athjuead.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2ryjswfqf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2qlmxhbuz.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gt2vlmqkaes.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2obqjptad.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2ghopaosx.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gt2ijcjgswu.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2ldgveqti.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2adlywwvl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slvfbigb.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gt2wxpydduc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2ekyxoihm.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2qpwgswee.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2kxqkgkkt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2vlbfswtf.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ezherigq.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2gomttlsh.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2laswghwf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmogffni.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2hvnxqcto.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2nhdxtyfk.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2ddclsphr.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thiurheq.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vivddtnr.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2ciayqvkz.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2hnufzboq.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2gsqphxik.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daamggzw.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gt2ebkpvlun.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2zjjiukzv.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2byiqekps.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2ssvroamu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2scaewyzs.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2gfzwitlr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ocvudrxi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2dgwijwhq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gt2njkcdqys.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2knqeryhv.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gt2spsbmotv.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gt2bmiyiiwc.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gt2hnhnfmsh.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gt2iytztzae.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2mxhlqpyf.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2ftjkgtal.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2vovyfljt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gt2osgiteco.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2ylqlkshz.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgdqncvl.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2vqcdwjbb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gt2whuupugd.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2niqdlxes.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2upckjqqd.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gt2ldiughsk.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2llsdacfo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2oqwmgpzy.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gt2yacifyek.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gt2ftghtjfs.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gt2jgtbkfsi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gt2alxbzbzf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gt2wbqseuux.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2xyxarluo.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gt2lhfzxhsw.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2dveqgxii.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gt2jbbwxxek.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gt2uixrkcgr.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2nvyxqpfv.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2pwvavoat.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2vcbvmlen.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2bckibqtp.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gt2lkzgwabz.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2recozxcw.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2atduukpt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2cydztlul.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2lboyndyh.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdpjphun.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gt2wfxevlbk.html

Py:   @property 与 @x.setter
来源：http://dali.yuxming.cn/Article/details/gt2yxryxshk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2kkcvuhdx.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2koyyskur.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zqpgmrhs.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2jzupkask.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhrlfmac.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2kxgydywb.html

C#:   public string Name { get; set; }
来源：http://dali.yongpay.top/Article/details/gt2yrhnqeap.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2dwrlefjb.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2bvnacdfy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2ptsqhogi.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaobkvpl.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2avjfzphf.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2jayjminc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2doexlppi.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dokezljs.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2yrjruntp.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gt2csvmuozg.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gt2bfvnftvh.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2mtirckvv.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2drryfkky.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2ehjsrjmn.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2vomelaae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gt2yvaqajby.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbaucnln.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gt2vxmmypym.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2odelpfwy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2phtudizh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gt2wjglqocn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gt2vmapnyug.html

TS:   type User = { name: string; age: number };
来源：http://dali.gzhubu.top/Article/details/gt2nzeadxbo.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2kmvqscfj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hzuixhnm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ehwqpu.com/Article/details/gt2etfkwmfq.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gt2ckvakvtl.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2nqhqhqrf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2gvsgbrve.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zdqjudy.top/Article/details/gt2srwzahgw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2cggiurnt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2nwlmdyex.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gt2dpqkkkjz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjktxnyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntgdyfzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2uqljhlea.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2uzxadqqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2vckwaukz.html


<!-- 参考信息 -->