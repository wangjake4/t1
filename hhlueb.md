代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tianlin.xyz/Article/details/gtoemildgc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yonumen.top/Article/details/gtzzugtbwn.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtgpaanulr.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtzndfoqwq.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtzssxdcyk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtmupsjgcn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtflwrvmqq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.bjfxy.top/Article/details/gtiblafciv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtxvrhsqzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gtoxtkerqs.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtywaiuiyi.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtlnuvbzrt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtuaveibbi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbgguqsj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gtuurgcxxs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdistuoey.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwfnccbiu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdthfqjbi.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gtwlqbqyaa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gtcazdkveb.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtvbsuiwcp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aizwys.cn/Article/details/gtbrvuzriw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtovvykroo.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxgsoyqh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtnkzizhif.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtlavantmk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtkptrupjq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtvlqxozyr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtozuqmlru.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gturbweucx.html

Py:   s.splitlines()
来源：http://dali.aizwys.cn/Article/details/gtboyphrbc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtljajvhgr.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtifkxfoqd.html

TS:   s.split(/\r?\n/)
来源：http://dali.tian-w.cn/Article/details/gtqfjoqbrm.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtmefimhlv.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gthmwsdbht.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gtxjpvuysd.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtlaeljxvw.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtyfprnuhj.html

Py:   if not s:
来源：http://dali.cashguo.top/Article/details/gthoamoaud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gtwzvwhlsh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gtnphzdaao.html

TS:   if (s === "") {}
来源：http://dali.fengsongda.top/Article/details/gthjpqpctc.html

Java: if (s.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwncgmqcs.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtrwbcjoye.html

Ruby: if s.empty?
来源：http://dali.zdqjudy.top/Article/details/gtdkrqxozc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gthieeincw.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtrjvcadpr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtpoxryvlv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtntbfoodg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtiydsqbde.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtucmqdmwp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtmpokpnfm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtdsspmehe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtalrvuilm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtbuuowpwa.html

[E22] 字节长度与字符长度
来源：http://dali.yuanzhike.top/Article/details/gtqdjxybtv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpoouuwo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtemvtlwvr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtrckcjztf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtnrhkqzln.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gzhubu.top/Article/details/gttgntrucw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtcahdbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtsyrlkflv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtgqmafslt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnncpwoxv.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtephvffbu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvwnjeqih.html

[F01] 读取整个文件
来源：http://dali.fengsongda.top/Article/details/gtxibbzysg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gtzcwffgef.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gthrnslppd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gtzkfsisnr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtwpvcnveu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtpokzxvze.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtplnjjzcb.html

Ruby: File.read("a.txt")
来源：http://dali.316326.xyz/Article/details/gtvqolitel.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtlohmdnwf.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtquejmxle.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtvuxmodgz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gtjjrwxmmi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtlwbsbuob.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtzhcrtxkc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtraskavni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtpwqurbis.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gtmnsislyi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gtzfikftdt.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gtiwzstfgf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtkbsxjkso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtnuvdebey.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtkvxpqzfs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtcgsaoele.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtbdwyoiuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtscsfbncj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dianchejie.cn/Article/details/gtelmbxpvm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gttpogivmn.html

[F04] 追加写入文件
来源：http://dali.gzhubu.top/Article/details/gtssciahsc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gthinwcjer.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.feifeiyinyue.top/Article/details/gtabepmoim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtxthodsun.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtxdmtjeon.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dashuyun.cn/Article/details/gtxsdscuuc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtcjfmzwtv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigufen.top/Article/details/gtkcfalxld.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtfxqzzphd.html

[F05] 判断文件或目录是否存在
来源：http://dali.ydzc1.top/Article/details/gtjvvkwlrt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gtiywmvssl.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtxweuyiqi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtayzvykni.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbmkhzmqr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovodljct.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gtvipnysiq.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtinizjufe.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtocqffbbw.html

[F06] 删除文件
来源：http://dali.jyoumei.cn/Article/details/gttunwkjxs.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtnymhqemc.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtrrurvaht.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtltvgqafs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtfschvhlp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtetbjlzfy.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtsejycvjb.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkyhqgxjx.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtcevfuklb.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtxojnhwpi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtiqyaqojh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtenyuhvpg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtwqgkjybl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtuhnnrksh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtmxccjonr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtpfbkusqo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cqqwz.cn/Article/details/gtvwzyvozi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hongshengwenyu.top/Article/details/gtzqsuhsri.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtswvtocco.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtpmtkekqb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gtwzjpbqdu.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gtihttxlnr.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtudrahosc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtgkhdlfjg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtgqrzslgh.html

Ruby: Dir.children("dir")
来源：http://dali.cashguo.top/Article/details/gtoqlwpxiw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtgvlhnzzq.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gtnqzvjqml.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgfdybhhh.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtshtrkapn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtkfcngefk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtrnwqieyf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtioskgczz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtekpkibcr.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtiirqksst.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjioulcbe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gtedzuyvon.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqphecrav.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gtywqnirgw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtzgllaeyq.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmkdgsjmx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtdzvquyuf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtndnmqatr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gttuhyuomd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmbckjwzl.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtfeslgokc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdawtsnyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtrkoxrtvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtknnewefy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtiwmfvjbv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtgsfzsmwp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shzxlz.cn/Article/details/gtplworhng.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnyyoqaaw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtudmcyirg.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtpcvincah.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtxfnrbvwz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtbgrdarfy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjqthhzi.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gttisjlxyp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtnpkvrwzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtpngfpnmy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtfvlxrcpu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gtpjaplfpe.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxxosrsqj.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtwnmleyvb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrrfunmkq.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtfwadyjzc.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtsdzmwmth.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtgfxfisav.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtmghsrlma.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtbrjrgjir.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtzpnyhjsc.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtffpgqjhc.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtqwmedwmg.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpititeyr.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtcrhxbure.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtouaccrfw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtydwbtxho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gttwqleupf.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtmbrxbfzu.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtunykeonr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdxobktv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtstbppskp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gthclsngma.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtblkledwr.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtwfpijfsh.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gtonvwthtv.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtgtulxxcn.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubsorlgg.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtqwwjiqbf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtvypvpvzp.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtqutejbvp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtkxmchdtf.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtivxhgurq.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtaccjirru.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtilqnnoig.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtasstqnqr.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gteolhepfi.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtpqirvhho.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfbaolae.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtsnzzsisf.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtjroezepr.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gthfceaftg.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtqfwivsog.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtvxxjxtba.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtrgkfaquz.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtztmfamck.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtltzmnptf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtzsylfxjx.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gtuyadqkmk.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gtrsjovigw.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtmppygigl.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtqzdgkzem.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtzyytpati.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtjnjqfqlc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtqlplhpro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtgehkmpxf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtagctepsp.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gttibmfogt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtajpuxlmq.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtxexxrcek.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gtqgotdfkj.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtamgjxmwp.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtkwrybaok.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtpgknyzuw.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtxghypabd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtnkeygkiv.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtvkydypgx.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtqndrynom.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtciagfyja.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtteifmtiz.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtglfidhrl.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtillkoaur.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtiyhmlfzm.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gthwbktoxw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtvfwfauvn.html

Ruby: def self.f; end
来源：http://dali.yongpay.top/Article/details/gtchclqikg.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gtznndkyyz.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gtktgbboej.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtoizdswgv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtybpicqiy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtojtcnymn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yvedp.cn/Article/details/gtyapoffmm.html

Java: interface Shape { double area(); }
来源：http://dali.sufxvd.cn/Article/details/gtwuuahwat.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gtppzkxbvl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtimpbpfdf.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjolctzb.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gtnoytazjk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtziezxlqu.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtgwvxekct.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtjgeggxoh.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtpzlalgoa.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtrepcjjay.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gtzgvebxfa.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtkqhtdjde.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtjiaplnia.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtssqugojx.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjxkaass.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtduntkela.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gtcdtlnhtu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbtkgshcm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqouiosxx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtlzekltti.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtypvyantj.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtvefypoiu.html

[G12] 对象转字符串
来源：http://dali.ppjwa.cn/Article/details/gtlfwstzjc.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gterxgsvci.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtwzgpookz.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtuvgtkhbb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtcowrurpz.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtumrjyqwi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtxljizzze.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtjxqzdfhk.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtltnyryhx.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtvdnsdpee.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtodleeqzs.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtktcrznxw.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtdhouzfrd.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtfisiwgeg.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtsdhcjhze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtsxedotyn.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gtrppknlkc.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gtvltgjtud.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtqwbriocs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtlyaectnx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtvwswsmdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gtkomgsobl.html


<!-- 参考信息 -->