代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtpgkjctor.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtboajeosd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtcobdudlq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhiwuduotai.top/Article/details/gtirckhdsq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtbduxpyhk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gtkeenehll.html

C#:   1234567.ToString("N0")
来源：http://dali.sxryk.cn/Article/details/gtfbdycbxd.html

[E17] 首字母大写
来源：http://dali.9152youxi.cn/Article/details/gtqzseiqmw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtynpazumr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangdashe.top/Article/details/gtpyrkxbqo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtxphnjetb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gtebauvilm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtskybnhgj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtyeghsbmx.html

Ruby: s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gtkumxfcco.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tian-w.cn/Article/details/gtepylywzb.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtkhqxultc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yanxiufei.cn/Article/details/gtvvicydlw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtrxmnmlff.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtgmhhjlra.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtmzeagcvz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtmhckdloi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtiskkdxom.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gtgcxlnisl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtbwxsmzya.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtsbbuezhk.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtfaxxilym.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtmyfvrzjb.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtalqxzjux.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gtvojqpqtm.html

Java: s.lines().toList()
来源：http://dali.xylfe.cn/Article/details/gtpzgtvrip.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtbhxbyxhm.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gtflhchxrh.html

C#:   s.Split('\n')
来源：http://dali.vqdsnc.cn/Article/details/gtzyutwdhh.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtpefxmpfx.html

Py:   if not s:
来源：http://dali.nanxuanxn.top/Article/details/gtjijjdwkl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hfpthk.cn/Article/details/gtfixlfmze.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzojqectk.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtwvatcnmn.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtrbqdfqkn.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtkoepabfm.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gtulcudqnd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtlpmgkwto.html

[E21] 超长截断加省略号
来源：http://dali.birdmap.top/Article/details/gtzbzpygse.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtrdzurviz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtjxyvbjec.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtwvpqndwm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtkpdjngqn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtwaefnyqu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jlsjyb.cn/Article/details/gtnwocsqhx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gttxpcrbig.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtxxmxpdrq.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gtohmyefbl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbyefihec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauocvxhy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gtxrxpbwlu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtuitcqeux.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtpgqrxkyz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gtwskaqikd.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtrpizamcx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtiwwxhvno.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqdgeghxi.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtefskywdr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpjubldez.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtiusvvpwn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfzwcuat.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hammf.cn/Article/details/gtlbkjoofu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtekhnkgel.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtcltndpwa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtwbwhhwum.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gtcsdrccnf.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwckdzrtx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtgammjhjq.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtwqygclkc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtqzmxaidm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtadwtblvy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtjayeqntm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtdbpbzvyu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtphsuyoeb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.iojbl.cn/Article/details/gtwctumctw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopgynlsf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hysaishi.cn/Article/details/gtfubgnpdl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gtbkuccmcd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gthbfuheti.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtpylgkfmp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtlbgpovhf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtokoesnkr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtsgvmgvht.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgdywbth.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.9152youxi.cn/Article/details/gtkkxggmyd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gtnldvciby.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqbrndzd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqwppxwq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtlvhqlzdw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtafirrgie.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gtwwgtfahv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtgnbfcpyh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtmmoqkyft.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtkezliccr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtrhiqqfac.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtrjruuzvj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gtrmilsyql.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtzaplrmnj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtnyrocjxt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqpjoslnj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtniuwdqsg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtkepywwtm.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtusvmbwwb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtamerntor.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtaoyszeyl.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtxpapojjr.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtxgefrxtt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtwefnoszo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkbxfpdly.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gteyixffoj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqhqugqxu.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgicuokrc.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtyyugqnnp.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtbrkoceml.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtdzctiitx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtguufkyvc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtbhlqdvth.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtawhpdgkp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jlsjyb.cn/Article/details/gtzelrjosd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqddwkqr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtfxvcqyqb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtozpfipaz.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrdqszrn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gtmrnupfan.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtmhjqhqci.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gttenkmqxf.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtqrndzlaw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtxsbpmjlr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtogflmkqn.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gtvunptuhn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtdvmmickc.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdexrzdl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gteaqljxbe.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtcobyblpp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtbdhlbfvx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtniyzquyg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtysgynuhi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtqcdbjywt.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtmjbleivy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtmgayxswd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhongyouzk.top/Article/details/gtskwhvcjx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gttdezsjog.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtuomisfct.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gteazebbcl.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtoqkggapb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtyewzskmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtcegdxygd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbmchciwo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwbpwcree.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtralwuzcf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvwuovrwn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtkhxyfxbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcqhdyacf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtklaxtuqe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtospxegcc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtzzukgvuk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbrpfypmc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtmfwnyrzo.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtejwplihm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtnjjvdqdy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtibyxhiij.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gttropchgr.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejmejpqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gtbkbekkcz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtkhfxhsqj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhnarkjg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtasqusvvp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvpvonrtv.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtlofajgxo.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlitutulj.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtfeqxyoyt.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtnzzlbecf.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahxvqiul.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtwgjunhfs.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtmluhirwl.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtoftaclro.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtjgmpygbt.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtfkymqlaj.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtvxsqaumg.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaulgonwh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtljklplhk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtruaamryj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsbhunndq.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gtujmczohr.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtuprhhoew.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gthjnoewat.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtkkffbuja.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gtpfvyvlfu.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtvgtdsuhu.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtpartqtkk.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gthwdftfdj.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtzbmumrna.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtruxguwzg.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejkufdig.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtqnemgtzp.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtooxgmhnt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gthzqcwbwo.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gtooqbrwuo.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtptiqxujp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtapxocvdh.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtugtxkdrn.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtdcilpfbc.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdjygudnw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtdmzbwqgv.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtxzatgase.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtfhotzafg.html

[G05] 继承
来源：http://dali.hfpthk.cn/Article/details/gtknphwmbu.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtezzklqcu.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtvjirbgiz.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtgaqnxrjw.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gthwrhgyee.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtxpbshgce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sxryk.cn/Article/details/gtuezxzgkl.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtlcgdzpvc.html

C#:   class Admin : User {}
来源：http://dali.yj202588.top/Article/details/gtysxnmfih.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtmszsalrj.html

Py:   def greet(self): return "admin"
来源：http://dali.vqdsnc.cn/Article/details/gtmmqwxltg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtbcthygxl.html

JS:   greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtvszjckuu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtlnqaiaot.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtsiprujdj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtkdhnnqmj.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtpdfqnnzw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtgljxehzj.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtkyaxzzgr.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtvdicbfen.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtueoliapw.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtlvhofdsr.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtsvoshmbd.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtlffzhngt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yongpay.top/Article/details/gtccebkfwd.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtwtgigfgx.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtvnlrsoyo.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gtkbtqzgnw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gttmprrgmu.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtmoewqtgg.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtbsmdegno.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtrrfmjpxz.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtnqizkrrm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtpspaqwft.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtmwijrjit.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gtzdphrpor.html

[G09] 接口 / 抽象类
来源：http://dali.ivvv.top/Article/details/gtngwtyjwg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtnomcgdah.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtarsmnedc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gttsygeles.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtwfbtrhbc.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtlfjxeozv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtaetzdoha.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtjdicpnct.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxrfucpcf.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtratdmtxk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtgqhxdthh.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtjgdsueok.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtixmhnmvb.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtgtnaoiku.html

Java: public / protected / private / 默认包级
来源：http://dali.snrcjt.cn/Article/details/gtsqdbnmdy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtankgmiex.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtyfnpvckl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtznfmhngd.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtkugxaxgb.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtjhmyiqdh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtaezdkylh.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlmsqmkqt.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqognmfwl.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtlpkyetzc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtghlauekn.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gtotehtiva.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtqqqhkotu.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtnoxfzsiy.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtbvupjbgp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtfycvwgpf.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtplwvkxro.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtykxlxurn.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtslxzvgwo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtknkasyhw.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gtyisyhzgx.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtputslaha.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gtnwasfocp.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gtfeamuhjb.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtypbnnykt.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtwfuwvojm.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtgdtoebwh.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtlycngsax.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtkbitmxff.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtwwwwzigp.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtlehkmoqe.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsnlxrbi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtqbkgqykz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gttozjnuvp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtyckbaqip.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gtpbhbupvi.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtewyafero.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtaglkyblg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gzhubu.top/Article/details/gtevolnkhw.html


<!-- 参考信息 -->