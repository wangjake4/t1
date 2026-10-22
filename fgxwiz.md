代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gt2iqimafnz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2sjfdecpc.html

[E16] 数字千分位
来源：http://dali.cashguo.top/Article/details/gt2tvykpeoz.html

Py:   f"{1234567:,}"
来源：http://dali.nwbrower.top/Article/details/gt2xmqydvcv.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gt2bjvamtvw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gt2xtyckjvz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2yovaeloq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwsmomel.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sufxvd.cn/Article/details/gt2jxppbbog.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvlirffr.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gt2vfhczwwl.html

[E17] 首字母大写
来源：http://dali.pycfn.com/Article/details/gt2nqlljgpn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gt2zpfkbbon.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jqgfzy.top/Article/details/gt2omqfwkqd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2gayjccwa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2cjcrfgpo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daria6918.cn/Article/details/gt2budnsaom.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2szqqjlbe.html

Ruby: s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2xcdwwjax.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ehwqpu.com/Article/details/gt2brorecbt.html

[E18] 模板占位符替换
来源：http://dali.cqqwz.cn/Article/details/gt2fbkqhlab.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gt2dzjzubpu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tian-w.cn/Article/details/gt2wsfvsquw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gt2iwcjtgyb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2vigbpjeb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2zjadhxbz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2wxxiulrx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangdashe.top/Article/details/gt2kocqgmec.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.c1oappe.top/Article/details/gt2njldaucu.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gt2qswkxcjy.html

Py:   s.splitlines()
来源：http://dali.wangdashe.top/Article/details/gt2fqhnjnpz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2fwovxphd.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2avuchuog.html

TS:   s.split(/\r?\n/)
来源：http://dali.cheryme.top/Article/details/gt2aaclwqix.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhxkzorz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gt2udejezks.html

Ruby: s.lines
来源：http://dali.jianghu66.top/Article/details/gt2lslrgzmd.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gt2mvfvlljf.html

[E20] 判断字符串是否为空
来源：http://dali.hfpthk.cn/Article/details/gt2ewippwnr.html

Py:   if not s:
来源：http://dali.iojbl.cn/Article/details/gt2sgzneeje.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gt2sgxxauft.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zdqjudy.top/Article/details/gt2wozqkovt.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2curfltlf.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2yrypzmow.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiktofom.html

Ruby: if s.empty?
来源：http://dali.havefunace.top/Article/details/gt2jmslgkri.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zycfv.cn/Article/details/gt2puzemrti.html

[E21] 超长截断加省略号
来源：http://dali.ehwqpu.com/Article/details/gt2zgexhfje.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2lesqeknq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2znndmoze.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2igqnimpk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqpxrqma.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2fbvdnfva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2kswqvhkh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2uxegorzg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2arpuatwb.html

[E22] 字节长度与字符长度
来源：http://dali.redwolf501.top/Article/details/gt2jqzndfkw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.0kj1m.cn/Article/details/gt2rhmdqdqd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2mrslkyka.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2ijqytnio.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2bcwtqoyz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2neljykuy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gt2ygmcfiki.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2jzrhjodj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2dsdkupnl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fkcnbwsw.html

F. 文件与目录
来源：http://dali.tanke756.top/Article/details/gt2dqrwqbvu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqoklsjd.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2qxifmdcd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenjidiqi.icu/Article/details/gt2avvehpgw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2fzsuhcjs.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gt2xzaxtlkf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gt2rfaghzeh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2xxvedhsx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gt2fuokjpkx.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2abebltyk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2dvtgzojb.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2zfdxjvlu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hisagkzi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuanzx.com/Article/details/gt2npkpeqge.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2lvfgnhmt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2kcgzhfzx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2etpnhyue.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gt2bhxxxsxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gt2rqjpfwen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gt2kgvgplaf.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gt2bczyrudz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gt2qysnryjl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2ggmmjuiy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2dcmuxpeq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2cmgzslsi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xetclpvk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2zvhncmho.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2yiykibqi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2iljtubvp.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2kiqerkbz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2kdibtqfr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2ioximcaa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwomneju.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2jkwthgmg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2cqhdvzbu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2yxdgkgku.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gt2ivnfmvei.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gt2glrcluls.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2tikjmzrp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2dvgvoowf.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2khfjibdq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2hrjydxst.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwovhcqv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2duebmzmd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2dxhurkwa.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2pitduuwk.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jphbqnpa.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gt2grdbqahv.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2xbpqiayr.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2qykhuhlw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2zzvhcyzj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2spvhzqen.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2hnsrjxcu.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2xjdjeuso.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2vmiqgtba.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbxwdwpq.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gt2rvidtghp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gt2zjzrkdfh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kockckiy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2nhybwykz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gt2ioaylxee.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2ntnhnaqy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigufen.top/Article/details/gt2cupfkasu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2tfaokbqc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xylfe.cn/Article/details/gt2sdfmrotw.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gt2sqnwftuc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2dupnieyn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gt2ketcynqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2scfrxklq.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2gyyoebpe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2cseiqfok.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2tllpxxkz.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gt2zjcoxhmr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.redwolf501.top/Article/details/gt2fmxkyrom.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2wobkdwtg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2pairqzzk.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2rkcckfof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2qctpcnbl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2jbchyzto.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2jetgczjb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2wplsgoxq.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2njxmvlmh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gt2lnzyuzgi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gt2knchjeoe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjqciohs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2pxguvvbm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2igbzvihq.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ogrbppji.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2qdrggdhj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2kofkoiha.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2rlxpkdaf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2grddijkw.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ulnfykvp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztcxkhyc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvohksxt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2tkybqeaj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2tzovycwg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcroqryv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gt2wczxswas.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2wzatwvun.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2widvrgtk.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2ykoqcubs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gukhipzr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewgejzsj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gt2aonyckgi.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gt2zubhycii.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gt2dbpokbtx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gt2zgqzgnko.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gt2kjajhggc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gt2wrtpkwgh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ljypcmrl.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gt2zvwtcyol.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2lguzttcv.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2rufjuiuw.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2deelawvg.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2fbkbvuan.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xcpnhlqx.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gt2obtlbkdc.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2nbnbuxyy.html

Go:   type User struct { Name string }
来源：http://dali.c1oappe.top/Article/details/gt2kjbbqzal.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gt2fmbbmyik.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2ygkoukxc.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2tesxuncd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2hgibskow.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gt2oztfjdba.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2kjmwvrco.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gt2cqvknzqe.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2myqwlpie.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2xgmmewkb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzewnbap.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gt2gldvmtnc.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gt2dczskdsw.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2zctgfdvp.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2fgrvrcmj.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2rutolugh.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gt2qsgdigfd.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gt2seqbtpve.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfyjjrwq.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2ytiouirg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttbrrgkc.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gt2deqlqjga.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2qfvpmcmz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2xfbhxzep.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzoawhtx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2sagqlnsi.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xzvakxqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2yaltnccq.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2vrbjyaew.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2zilagrzg.html

[G05] 继承
来源：http://dali.aizwys.cn/Article/details/gt2goanssgt.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gt2sodimijb.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nxyvexoz.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ixitspvt.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2mturvdau.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qppchwha.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2kdihokfm.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nsooukgw.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2mebanraz.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2ngrbsmur.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gt2undwviar.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2gozgzwyr.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2pcjguceu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2hrxmvvxw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2dhmkitlk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gt2nngczynt.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2vfpihzgz.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2jqmuashr.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrcjjfrr.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2uzecumdr.html

PHP:  parent::greet();
来源：http://dali.guannengcc.top/Article/details/gt2ebdzrjkr.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2idqusqbz.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2kcnnpktt.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2tpavgnps.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2usfqorfu.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2lmjpldtk.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gt2strcyrwg.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2vkpuyvtn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2oivdlrps.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2mdpmevkm.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2zshrbrhw.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gt2dmvzjxpu.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gt2nltzxdhk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gt2fslfiugh.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gt2hdqzyloq.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2pdghyzwl.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2orlopmuz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2fbppyedy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2eugjkebd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2pfgcefxk.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2rpogrvji.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2tmsjecsb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gt2qmbnwmqb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2cycecbkd.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gt2glbtbtxe.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2mqwdytmg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2ihcmshad.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2jkeggofm.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2sotlmdnc.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2rucpbjff.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gt2tjucvlgo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjtvvvhr.html

Ruby: public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2htcrkzrn.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gt2yvipwvpy.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2nmamgwqq.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gt2tmtdmyov.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2qubfecxn.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2hdaqoqwq.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2mdrhkelr.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2aycqwkqi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sswcxsye.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2qvrblftk.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2zgmfsjko.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2cmrcqqjs.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2valtuirl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2obiyinst.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ofyjwyiy.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbbzjnuc.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jhoanpyi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2qvngjabq.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2clrcwyeb.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxzbnbwy.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2xkcwbfft.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gt2yqlaowsi.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2lblvqfoc.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2cftwyouk.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqaqwnfu.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2rkvrfgmg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2gbltvkqu.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gt2vktgtsol.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gt2hgvoaslf.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2sezxiaje.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gt2oktezfdq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gt2bwdotrhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gt2spbpvrve.html


<!-- 参考信息 -->