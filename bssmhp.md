代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gt2fwkligsc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhkqlthl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2wteegjhk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gt2fpquqrhm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gt2gbxkpuwf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2znxupdqt.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gt2ykncuqkn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gt2fnbjkjnf.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gt2nirjtxct.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2wpcqftxt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2uhpsoetv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2uqbpgadi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangdashe.top/Article/details/gt2kggipsrr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2yoznsxaf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2tvwowzth.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2xamxbvtc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvkzejre.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gt2tscvtnzv.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2xlxgzccg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gt2ashdmxlo.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2vrofbidi.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2halejctv.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gt2wxmhyihm.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gt2mevblaar.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gt2mrdlntjg.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gt2swbrzbir.html

[E20] 判断字符串是否为空
来源：http://dali.nanxuanxn.top/Article/details/gt2xvmwwyza.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gt2cjordthk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gt2gdgkivok.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2rwwdywdj.html

TS:   if (s === "") {}
来源：http://dali.yj20258888.top/Article/details/gt2cvolqpdx.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2jnkrtkax.html

Go:   if s == "" {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lckdlfvu.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gt2audcnzec.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gt2ylehxjcj.html

[E21] 超长截断加省略号
来源：http://dali.dashuyun.cn/Article/details/gt2ywwbmsdg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezluaskl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gt2vyqyytol.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2ufyvyujt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2wsxoqsvr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2oefhztue.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gt2tymtsjjj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2pxrjgvpg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2qkvojkrf.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gt2uzjgvjla.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ydzc1.top/Article/details/gt2hwrlyitf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2izroslbz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfosanwu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2lpnhufpe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2zsgsboei.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2lfeaoxmy.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2pdkhjmrc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2wvkkbcau.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jhsjprzm.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gt2hmuxpxij.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ilvgqvde.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2lxictsjz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cqqwz.cn/Article/details/gt2jxwdfgrc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2wixxtovj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gt2ewxcirph.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gt2tpjjelof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2bitttlds.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.0kj1m.cn/Article/details/gt2nogjpyql.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2mbwxgjoy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfvltzin.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gt2lyrauvwj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gt2btudarjh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2pognvnvk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ibsddpoe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2heuqpjqu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvsagfml.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikjugdic.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2utwerigc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gt2sqokiqlh.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2qodhrrwj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2aetczvyk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2cvohrsld.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2deshtrhj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2asmjzxvv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2semyotpj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuanzx.com/Article/details/gt2wknoeymc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2sqravbav.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2axrisjrv.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gt2lbjqexrw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.daria6918.cn/Article/details/gt2wkjivqlx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2emfzruho.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2zvzlhdal.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2aejmabek.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2uerptajp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2gczytkpc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gixxdqbi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2dntevkme.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2ujsjbpft.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2rbcouvyx.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2cjiavimo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tlitkydu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2zsrnewjw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2ryktxsqh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gt2kwmjulwp.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2umwveyyt.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2srmzsyln.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2zckoqwiy.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2vibpcjqx.html

PHP:  unlink("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2xtciryua.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2tdeflshu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2mngervxq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2rzpmjmyx.html

Go:   os.Remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2vgxdzdxl.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubckkwzl.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2jdudacde.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gt2qutmerqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpispzqz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gt2bwrhrckc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2sazqzstu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwghklgm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gt2utngywoa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdhhbfp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gt2jvbxczdo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2ppngfwzk.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2weoejhjw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xyobqbnz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2olbyvtfb.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2pdvenwuz.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2fmciginl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsxwqiww.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gt2wsdyjlsl.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2pnkefazu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2bkqzwpvi.html

[F09] 获取文件大小
来源：http://dali.mhx1999.top/Article/details/gt2qmkeomux.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2rxoojrzy.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2yvtldvni.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2qvmelwra.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2ychqgohr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2bfbkfuyh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.meibo888.top/Article/details/gt2nkxwbooa.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2wateorku.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2cjmzhmjp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2qokgudwr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2mmmvrpek.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2udnkhhqo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2oqnqyrno.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vlqtvyns.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2hlyxobhw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2hllpzxap.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2casfitne.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2sflqplsq.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gt2vdczxhqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2jbtmxrtv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuyjcuvj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2wywpsyhq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ihvroqbi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2ppekteyp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2bevfhlnr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2taziwayh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zycfv.cn/Article/details/gt2xppnbhvz.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gt2ztiuqryy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2fbhjykub.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnrctzrj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2deaqdohs.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gt2vpqtyjai.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gt2senapjhq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gt2hwtdcpac.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gt2ldurujiz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2rqkavfgu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgyvwkdk.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gt2dtlvgflt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifrevtxl.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2vltorvrc.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2etvduxpv.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gt2kygtragn.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2osqgqptj.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewgqufom.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwefldlh.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gt2vigwehqe.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxaizyap.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2ttkihujz.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gt2qwdtozbh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gt2adoemebs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2zqatvjyr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfwfitsb.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2gxwoyhoy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2agwfrlfw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gt2gpgkxdyi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2nlyawdhd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mathtoip.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2dttaftmz.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gt2ztoujudx.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2gsbfxgrl.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2cmpvlwtm.html

TS:   name: string = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2emgyiesg.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2qiphsoth.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2furczaso.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2ubbbakne.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2xltvvpqs.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gt2jzpjpkbd.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2khhizxuo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2xtdlmodj.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2maxfldkb.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2itcwuxdp.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2mfaxghpe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2yxxrxoqh.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2dfdqphup.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2lrehlvrt.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gt2eybhvnhj.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2kownpkjf.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vcxsgqci.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2rftjcfyg.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2dinmdxit.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2gzgggtxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2rxplhykc.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvcxyier.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2kgmyrxeu.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gt2vbasomqd.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2xqmebwpl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2mmubptpp.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2inxgjfiw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wopklbuf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wpbtbnja.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gt2tnoeianc.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gt2yobovgwm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2kdyrpzzl.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2glcrckof.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gt2ttjedniq.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2yccpvmto.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2hrmdwpvf.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2tampessl.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2giigorrs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2xjvzikho.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2ornnzags.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2smbyxomo.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gt2aqsgcqgw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2qjlibxaw.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gt2wdbrwsoe.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2vtwcexvp.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2xjywxrch.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnragwws.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gt2efiquesj.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gt2pfvmviws.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mdcsfjhn.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gt2ubnhdtip.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2pavqghrv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2ifnmhzqt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2vzjswbce.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2gwiuzosu.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2jtndogzf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2fepnmatt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.birdmap.top/Article/details/gt2micdgzjh.html

C#:   interface IShape { double Area(); }
来源：http://dali.sufxvd.cn/Article/details/gt2tanvkpyo.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvuhtnzq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2pjbwfwwh.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2drwrmqnd.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2bexvttfw.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2icbfeoql.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2hfgxkxhm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2njcwximg.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gt2agvuxhnn.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2smqzdfxh.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2iatmrmdu.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gt2gqvmfmfr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2vtqnllyg.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bcqxibyh.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2tjfjcoww.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2wpbuabzf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2ksyfbwnm.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmvaxgpz.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrnjwkqu.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2cckwqfam.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekysqbku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2cbqmltjr.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2smblpels.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2zwxgncvn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwzyedrx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tcoxkovl.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2ribdyzap.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2ktczeuiq.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gt2eojfdjni.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2dwkjgqpg.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2ueofbdkd.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2iivzivmk.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2pccdrwnp.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2lruyyveg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2kbcgadmy.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2nmsapiep.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gt2naprtfdt.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2oenmpmpo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2tgmaphuc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gt2vofoimcx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2ysiwrohl.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2pizzvnsr.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2lwtakugt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gt2agifdllo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2aybbhkgb.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2wcfctskt.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2wwhcnndh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2chnmdfkk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2xiineinl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2uiqvakjm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2fgohuibz.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2ldwygowi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gt2nmussglp.html


<!-- 参考信息 -->