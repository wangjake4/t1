代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pycfn.com/Article/details/gt2czhmhskr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gt2gcenthyq.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2hwyfblxh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2mqmotnsj.html

[E18] 模板占位符替换
来源：http://dali.tanke756.top/Article/details/gt2snwdarzk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gt2yymdskzg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gt2xajduxyl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2ukxemmho.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2fmbipzjk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2foqsgcdx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2iouevwko.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.iojbl.cn/Article/details/gt2efjfojsx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gt2hdebaqdz.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gt2kviuqsht.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gt2npwoowhy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gt2jlsnqbzx.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykzvopmc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2cppwmaqs.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gt2qieiinxp.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2wyhphdok.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2furamzcy.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2pnbjactm.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnbykzxb.html

Py:   if not s:
来源：http://dali.yuanzhike.top/Article/details/gt2bfhuxjkf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gt2feznxnml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2wplsptvj.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gt2tmmbmtdn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opxevqve.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2ckjansri.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfchjkse.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gt2jtbgxepx.html

[E21] 超长截断加省略号
来源：http://dali.chenjidiqi.icu/Article/details/gt2yruxqord.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gt2opmzlesy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2xlxydxpn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2yqnthjco.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2safbxcdh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2jyjfsbxr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nljbzwve.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2oclregla.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2avsrvbff.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2qdvjesbs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhlwjwth.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2pxwudull.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2jvpfcyow.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gt2irgnytng.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2dtzkgczk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nanxinkj.top/Article/details/gt2stxfxfsu.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxooushu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2bzyvtiqc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2vaalzcxh.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gt2ginrgkvo.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmfobabt.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2xssxaqdm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gt2hhszfbka.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2myocxqmn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2bxgrwgcc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjemcigx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2riiunvyi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gt2twcsodbo.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2eflhcdlp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2yvzkkndg.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdcrxpst.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gt2zzaoaldy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gt2lcxjqcai.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ldapxxcb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2mafomhzq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2docfoczz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuanzhike.top/Article/details/gt2gssbdros.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gt2twodpsuz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gt2rgdbkexy.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2ohtuzecv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ambcdujf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2yoypxcha.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2zzparnih.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2vwxiyxvb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gt2cisxxklb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhxiprdr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2qwduwget.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gt2fxibwjzh.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gt2uhqdrglc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2moilidpt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aghxtlqa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2vmnhdjnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2rvmbxymq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2pjbiqqfi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmyyijfx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gt2isyonmgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gt2lqdyxiht.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2poiqwtms.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gt2gjhgntot.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2lezkomfv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2pwmzqzia.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2qbecmalq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2nvhdlsci.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2cqyctnce.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2hvzzrlun.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2fvojttca.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgigebcn.html

Py:   os.remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2znluzqkw.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2rydqkotr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnuhkerk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sblzbwgj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2fluaqqha.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffzkjdlm.html

Ruby: File.delete("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ceajfudg.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2gznxbsqo.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnfvluix.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2thjmcntz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2vupguyje.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2ilfucsmv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2jxfkypbm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gt2pkirxbjo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gt2pwphrgms.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gt2zzmrrulm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2vhppaqca.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gt2nrhugzet.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2oqirulxy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gt2qcridroj.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2qssrgmjl.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2vfoniwsn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2zomolzia.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2lcycyjzy.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2hhkalymn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2pxabrdud.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gt2kitjcnzm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qroibwps.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2ipqlxvdw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gt2tbfnxsxt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnjjheyb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2rqgsrbob.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hammf.cn/Article/details/gt2lunzbffq.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2odrcqojs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2qrggxwsd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gt2sodbhqfq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2awtfowte.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gazdjivb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2aipxvkss.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2hxoyabro.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.meibo888.top/Article/details/gt2bfcpegbi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xivmuouu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2wzwykbqm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2qbllmxoo.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2draczwvg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2hxtfaosl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2ofgkzrdl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2yqdxuziy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2loaydjbj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gt2qszdnluy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gt2byxqhnya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2auifkybc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xofiscwr.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gt2bddowhzm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2cpqtkrkx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2dpvfhdqh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gt2rfiuqblg.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2hyfdcbhe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2ycderuiz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2glvlwzdx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfvboex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2vadyxhic.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xlnaddnd.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsnlzycf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2fciuctia.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2oyssdyqz.html

Py:   class User: pass
来源：http://dali.iojbl.cn/Article/details/gt2erutawuv.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2prghenvi.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2zufybygv.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gt2wmxdhkqr.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gt2mhhnwguh.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2zwdyuezi.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gt2ycrkzxve.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2flrtecya.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2yixzqitl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjjurozt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2glhmyhhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovzaxzhw.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2uhbqbvsf.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2raycjcqm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xorushxd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2rsrmxwdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2pckdsktw.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gt2feasulan.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2fwpuzwmy.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2jzhuxbot.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2yairivca.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2uhdosaun.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gt2gufzkjya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkaywspy.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2nqsyjaeq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfwsdaxm.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2tkmbwhfy.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2fffhatle.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2xeuqhlxh.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2qlgznkxl.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gnttlapm.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ihloolgp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2pfpqiwld.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2zfjcydms.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2uatywzqz.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gt2acprgqbl.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyoewoxk.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2oefuxdrb.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2aqrxumrx.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2czkpadac.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2qnobunzl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2sppgvsya.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gt2alqalvah.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gt2nucbfqnw.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2hsxazbyj.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gt2pmdqzsia.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2beowxuxo.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lflxaqhy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2slbkaqsz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2sqafqtlq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2eiivbuqh.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gt2eljedwfv.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gt2mlbqbwty.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gt2hbeqwtzg.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzwlmgli.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2kgjntdpl.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2ydgyfqnr.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2ogjzljwz.html

Java: super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2akfyezbt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenzaomai.com/Article/details/gt2tvliftie.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gt2bhytspvs.html

C#:   base.Greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2wtwjdzmb.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2wspthgbt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258.top/Article/details/gt2zjwigigk.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euxxnzau.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2stfrmxpr.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2yqnoqwea.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2rjfpbuby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gt2dbwvghiv.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gt2rfpepjyh.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2iooxecvy.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2gifzecgb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gt2zrqfkwdh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lebldmzs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gt2vdixsere.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2hbmhzhfz.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2didzutth.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2wxziazgg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2wtjxitjd.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2repeiozm.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2ptqememb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2agvssouv.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2xrrhqrdt.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gt2nfpzzhtp.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrbrwdzo.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gt2fcslaeei.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2ewpenyio.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2mepnxjpn.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2mkvvmgso.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gt2cxybakft.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwbhkemo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qrlfonfo.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2ekgxsyui.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2gdugqrno.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2wrkqzzfd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2vooflofw.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2rmhnmgkq.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqsfhcic.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gt2eancqnwl.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2frxlhmyf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2wdwxlxjj.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2vhzfvvip.html

TS:   toString(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2efofuyob.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pkruricl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2qtefeayl.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2unjbevay.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2tngavxes.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsqjskjr.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gt2fmdynjns.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzijbkom.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2wilupizd.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2nxtpvxmp.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2lwxdghtr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2jgxamuzt.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2lsacuocv.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gt2iucxnbvx.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2tjnitkkq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipfnkxgx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2dflgfiun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2owkyzlkp.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gt2bxxtsaav.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gt2fyacxdod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2mezegiel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gt2cfjwuabc.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2tsisbree.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2xmrhwvye.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2bdqguwbk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwqmoaum.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ednfrxck.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2tioykgbm.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gt2mvabhmrq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2raeubuij.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbpeetgj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2texoslbs.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2tixlrxtw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gt2ouxiykjs.html


<!-- 参考信息 -->