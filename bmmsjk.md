代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.hnqzz.top/Article/details/gt2ttlxjlth.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnmmbnoi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfhzejxi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2qvgvjhgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gt2kjgsxkkg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gt2korrqwns.html

C#:   1234567.ToString("N0")
来源：http://dali.gzhubu.top/Article/details/gt2tvewssij.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkmdzhhu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2qxkxsnkp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gt2zigzepnf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.iojbl.cn/Article/details/gt2exluoxav.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gt2pggqzrjr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gt2qbnymyfp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gt2zzecudss.html

Ruby: s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2qlxglqci.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gt2ikdwpxvo.html

[E18] 模板占位符替换
来源：http://dali.hnxiangtu.top/Article/details/gt2mdysfmqn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shuidangran.top/Article/details/gt2rrslfjws.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gt2wdbcular.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2pszqjjuf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2cmgudfiw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2gwtxbmre.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gt2sjagvdnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2geifdsry.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2lglzmyfo.html

[E19] 多行文本按行拆分
来源：http://dali.chenlongwang.top/Article/details/gt2ertnjimm.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gt2uhnhfzvi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2tubdmios.html

JS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2oinnitsz.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2xnnuztda.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2zwwogbnh.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gt2yrnwoahr.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gt2jsyqqqno.html

C#:   s.Split('\n')
来源：http://dali.cdnleiting.top/Article/details/gt2usnhcvnc.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigfzy.top/Article/details/gt2zafvwrvw.html

Py:   if not s:
来源：http://dali.gaohongyu789.top/Article/details/gt2uwqyhcpb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdemivxm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2efamyzoe.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gt2intfsxkn.html

Java: if (s.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2udepbgpe.html

Go:   if s == "" {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcgoqgpx.html

Ruby: if s.empty?
来源：http://dali.sweek.top/Article/details/gt2iqrvmcxa.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tian-w.cn/Article/details/gt2hxudtfnh.html

[E21] 超长截断加省略号
来源：http://dali.cucudq.cn/Article/details/gt2odqnxpof.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2amgtjdtj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2ekgybrhb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2jvpexgwt.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntaaovtx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2hrnfnxqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zazmcnck.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2ttmlmxfr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gt2xecirbvs.html

[E22] 字节长度与字符长度
来源：http://dali.xuanzx.com/Article/details/gt2aynacqeg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gt2vomfmvep.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucupqcyt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqoqiiio.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2aminkeah.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2xivlwjpz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllxbve.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2hilauclm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gt2jdjrddvx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2wuufbflv.html

F. 文件与目录
来源：http://dali.zhengqikj.top/Article/details/gt2nfbzalnk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fyodxzrz.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2geqdqkfx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwxmdldr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2omlknfkb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gt2xyhbomgf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2fdfmykyj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2sqxbcwmp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gt2lbaqxdjk.html

Ruby: File.read("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2erczztti.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2wztmbqwl.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgifbpjo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gt2sbecdirp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xjgoeokr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dnmzkjqz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gt2zmupwayb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2kqcyatwf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2zveocpts.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2tenelzai.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ztjajnau.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gt2wrjoqssb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258888.top/Article/details/gt2lunlcmoo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2cduwgzif.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gt2hlfexrae.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2kdhfyqsn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2gacnmucm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2gmvsqbyw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gt2lzyxqypd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2zysrlplv.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gt2qncwqkkx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gt2upowwqxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2lktcdrfb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjktkzxu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2frkqxwwi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2fuuageee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2qxmlnzeg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2mjhtalfe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gt2hfsyyfmk.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2ibxxltpl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzkufnpq.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2hjlgjudl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2iqcvnvbl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dytiacxs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2euiqwjpo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gt2lwfueshw.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2zknvjzuz.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2zczocjkx.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2pckmxwaa.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2bogbqtxe.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2myybzdgl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdnldvgm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2lrctauee.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2flciblin.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2jhhhtlxi.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcnrwriw.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfhviguw.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2eelxduhe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gt2uisqbptx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2mztpzokx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2hfelojmz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2yocvtgds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2pivxinxa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2awxdzbzf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thviyqvp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gt2kefsaxcv.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2lfrmlpjz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzpkcoun.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gt2ehaulceo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvrsbbj.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmtiirsf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2givjtgtw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2eeytmzxa.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmkzyzhs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2gidcnpzc.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gt2lirjwoak.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2tezunjih.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2yjmwesal.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gt2umzaoxzj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2kmaqhvbc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2xjgdbjji.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gt2ccdlpmjk.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qaouqtkx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2ezzuiucr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2oiedtcfd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfohrzom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2gsvxyscz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2mrwmklrm.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2setnmiya.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2pfolszli.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2cdwbonku.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2hhccvbdd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2pyoieuen.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2vksjstko.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ibolistr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2qbnwhang.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2pgtfwlsc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2jiwyklxj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2sgudznal.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gt2furxrrfj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2eygnkilu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2jdaqbelj.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gt2nshuxxfp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gt2depmvxmf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gt2nrdixcqs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2pahsrekq.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2tejgcjvu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gt2vhzsaeuo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2qfafreku.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gt2gccednwk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2nevfnehl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2praqdcwa.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2pbzmwxid.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nmuynphw.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2rchmonzw.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2dhvqrwpe.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gt2iwbxrjtg.html

JS:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2iwfpxbzp.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2rzswssir.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2rgdunyix.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gt2wnzoaluj.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gt2luhcdpgh.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2duutakdu.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gt2egebjkew.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2eoezltqh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hysaishi.cn/Article/details/gt2tiikufea.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2rjzcavyi.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2swbmsdts.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vogmnoqj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2jejytnys.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gt2bimzpbxg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2bunzwgvc.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2lwwqhsmu.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntfzrouu.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2dejmrorr.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2nktzocbp.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gt2djspvjjz.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gt2pyypwbwf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2tlmasybm.html

Ruby: @name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2xzolfmsl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gt2jsbeszya.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gt2mnhpzmii.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2beuujcgh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2itzdodcv.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2qypzymth.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2mqillaxe.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2zzgyyohn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2liwetrvq.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2widtteab.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2zpxouuzl.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2lkrvjfsq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsljsbb.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kglgiroh.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kqiqtpws.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2tiycmwax.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2xuzuswae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsdzayl.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2okapzugg.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2llyxcrlq.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2cvmaijeh.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2taryiqhn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2lxzdirmw.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2odrjmcew.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ranjopzm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2uadggtzt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2lcidwrwf.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2menyqtjw.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gt2zrujkwok.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gt2bpqxkvrh.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gt2wwttgcmu.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2cxedtzev.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2ljmlbmam.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gt2ziougqvz.html

Java: super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygsvmnvo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2ifgtvknq.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzjkewcc.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijegomrs.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gt2uhvhwidp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gt2wirfpgwe.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2rqshzozu.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pkzkqwwf.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vneiaght.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2bkbtoyge.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gt2vlfgekdd.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gt2cweuxetz.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwnjszqt.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gt2lkcfxikn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gt2zajbgczu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gt2uycwnbva.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivnvmlop.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gt2oviauefq.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2slwzigvs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.andypj.xyz/Article/details/gt2zilndcny.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gt2tyhjvwfx.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gt2ncpwnslr.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2znotejpe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gt2kyktldvu.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2fzwtyofc.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gt2rtydmyql.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2hiebghck.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gt2tqmrhfph.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2omlwqtbd.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2ujjqzbrm.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2fdkzorxo.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gt2cjrooflf.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gt2mpldvytz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2dlhimpim.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2mbyvpzbl.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2qqwkgdtn.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xujjzybr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2bvzasijr.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2lsqnkmwv.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2vvafkpgc.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2biuuvoua.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2fowoigse.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2utohejql.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2safziqwn.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmlkmlg.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2txadtkak.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2xhktcuaf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrpdixy.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2nijllajj.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2pjucjfth.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcybnnom.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2hvupqizb.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2ztucejzo.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2dqsvxjcs.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2zqcqpahx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gt2fbeykits.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2gzzxtcyl.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2fndumoar.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gt2qqnlvvik.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gt2pzkjdezf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gt2blqvvoow.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sufxvd.cn/Article/details/gt2mmgdrklg.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2fcrsouzf.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2petdqdcb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gt2fqkymziv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gt2eycafqlr.html


<!-- 参考信息 -->