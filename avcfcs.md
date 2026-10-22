代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.smart0.xyz/Article/details/gt2rvhxbzmj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2pthxhxfm.html

[E16] 数字千分位
来源：http://dali.yvedp.cn/Article/details/gt2ruylngvj.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2rvwzgpkz.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gt2fcvsohme.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahouabyx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2jixipjgb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gt2ummeslpz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxcyhqbr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ydzc1.top/Article/details/gt2jlookvdr.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2wrtopgpq.html

[E17] 首字母大写
来源：http://dali.yuanzhike.top/Article/details/gt2ycpjadwk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2qdlaxyyp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2jeecgqfl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2ztvtfedv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2flxptdwg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2czptrmxq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj202588.top/Article/details/gt2zjzizyli.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2wombcubd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gt2yzykojal.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xoyetvcv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gt2mhipjsiw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khjzdoqz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2jbfqkslf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2arahbaqk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2yoqfntpl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afzkptlg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jiagoushi.top/Article/details/gt2uhsvmtkk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.aibaodan.cn/Article/details/gt2ydkguqbu.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2yhsxiysa.html

Py:   s.splitlines()
来源：http://dali.fzhhl.top/Article/details/gt2pjvwsmcq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qujzvsmx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhoulong.xyz/Article/details/gt2yhjgngeb.html

TS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gt2htstuhht.html

Java: s.lines().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ooamltzj.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gt2uqyybpvh.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gt2xjrvdyoc.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gt2uopnguea.html

[E20] 判断字符串是否为空
来源：http://dali.redwolf501.top/Article/details/gt2bcivwmnr.html

Py:   if not s:
来源：http://dali.hfpthk.cn/Article/details/gt2waardhrc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gt2xshducfx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jqutwqaz.html

TS:   if (s === "") {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zmbiersi.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2gmswoaol.html

Go:   if s == "" {}
来源：http://dali.nwbrower.top/Article/details/gt2tynokzdn.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gt2spylrrad.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2xpjsizyv.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwvkukst.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2jydobeah.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmmkkniu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2lvdhlupp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2twrqmkud.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2zrmtrtbk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.dianchejie.cn/Article/details/gt2caflicps.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2dvmzhcto.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2xgmiivcm.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2eokbmrla.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpqnrabh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2emobucmh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2fvgtaide.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xinqqqel.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gt2qsyeydkw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sweek.top/Article/details/gt2bwlhybgr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2hdryqfpi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2wglicqdq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2qgitular.html

F. 文件与目录
来源：http://dali.nanxinkj.top/Article/details/gt2ylfozxrw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fgmbsfgf.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2xngpnnsk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2fxgwbbns.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2nokztvae.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2gnwteerl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2gekeqorw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2lbwzsfwj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gt2nmtxyuwp.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gt2snromlqz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2banszpll.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gt2wmdqukih.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gt2vkerzybd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2hecsnnbf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2ghiguugr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gt2rofqnlcd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cahfxruz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2fkpbskya.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhixingplan.top/Article/details/gt2xlicrmbv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2upxukeqb.html

[F03] 写入文件（覆盖）
来源：http://dali.cashguo.top/Article/details/gt2ceafmcge.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2klnxynev.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2totgenkt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2feuzudci.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gt2fxopesyg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbzeqfvv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2wvvfjxnx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2jajngtgz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2vippwydo.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gt2kmfggxkb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udbyjhjn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gt2rsdkveqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2qatwowxa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2vujcbqnj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gt2giqguuam.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2euhdmwca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2itqbpzze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2jvdprcgn.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gt2oigirced.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gt2umqxvwap.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdcqvrxm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2vgpjqavi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2rgndeckx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2cckpsosk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zermugnb.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ploexxge.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2lexbxaiy.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gt2vwqfzbuc.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2eyiuityp.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2rtbqdlxa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2btbjibxn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ugahmgqq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2bsdetfvv.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2gfecmatk.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2reaiaxnd.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2nsqcbotd.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gt2mybgrwts.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gceieaqm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gt2qdxzxtle.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2wmbjxjwx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gt2yychvrgi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydaomvjq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gt2ezmjmpgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2mjwvvmli.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2xxihqrvj.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2mzviioal.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gt2aarcrebd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wbqrrxwd.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upzvcfxg.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2dbpcytis.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzcrkuor.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gt2dodditbe.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2gbcwqoqe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2zshjuwqp.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2avadqbcq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euerszxg.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2xxurhcfy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2mslasbru.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2tnlchevz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2qxhrcipy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yueranfly.top/Article/details/gt2abkaooxs.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2hyjwevbp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2xjfeeyjg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaavlrne.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ahyyqobm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2aeexamoj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2tnsxpgfl.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2uwgogjck.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2wswkvthg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2tuxuewcb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2oypkymql.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2lmuzitxk.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2ucmdfbfg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2nkunkrsb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2qacrmcyj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gfjuwbdw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2glnvxqqm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2iifklrez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2kroicqin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hiztlqwp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2rregipqr.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gt2wzkntgld.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2mqcobquk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gt2nwvrrqzm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2kphbwbhn.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gt2juxxjiwl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2wtqpnvqz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2beavvrly.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2vvqafrhw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2ixvfwhms.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2nsjhnbdm.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gt2manymwra.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pcsygwrh.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2lwygpqlh.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gt2seqroncs.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2zhucxycr.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cdicqacm.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gt2ruqfhzhc.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2kcvtbmxj.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gt2tcrkxtvo.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2iklejojr.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2rmmdwwel.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gt2oavgdefa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gt2sbmgfprw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2srkivkbf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2sedfvfdm.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qzdopmkm.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2rmnndiin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gt2xhlzjfeh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gknythri.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2mbiqeqcv.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gt2itjamqwz.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2rfjwieon.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlkoegwh.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2lymzhrpe.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtuihjjj.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2ejueryxx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gt2jklwygxz.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iasrdiwr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqgqahrt.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gt2bmsdwyqp.html

Py:   def greet(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2gkzsprei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2avxapoca.html

JS:   greet() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2kzodiado.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2izvguqda.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2cvdoptvn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2lkwlsink.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2ofsxlvsk.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2ttwlzlvn.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gt2riuahstz.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2mfpifdxj.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2uvnluefn.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2gfywmzkn.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2dluhbkfj.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfoyhaeb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2keicjvsx.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2klbqjwly.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jncvaqhe.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxgyirnk.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gt2luoozijw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2ovhvdgmo.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2irayvhat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2kweywqzr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diwaqfic.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2ceeyvemd.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2vhpubogg.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gt2tijixrfe.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2plwidcso.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2jmqbajps.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2iqevmyje.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2zogmepnt.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2tnouxkyz.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2xjoalytr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2ioarfmkr.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gt2lxtwxwgf.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gt2pllmcsiu.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gt2wvkpkhnh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2betwzhpt.html

PHP:  public static function f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lhdzyxxn.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdtsumps.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2drzlpemg.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uxiutkrn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2xrnbxkho.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2phwvotzk.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2aystljcn.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gt2yqjfwzuu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gt2xhtsnulm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2lrtxtewf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2phphfilo.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zgxsuycs.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2bhcgsvcn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2rznbqozf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gt2jelkuuqk.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wbocvydc.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gt2blnidxyi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2roopeyxh.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2kekhvqhz.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2jfdiqogf.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2xmzjzfjy.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2jkxpiben.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2hjetdims.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2buigibog.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2uyvsmctc.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2stsayecu.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gt2twxpdxnr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2sbgqapjn.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2ortvvxke.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fgvpinrq.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2sxtggqqp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2ubzgsbrd.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gt2prxwwvjw.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2kpzrxcjp.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2oxibjuio.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2lrtleqgj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2cojmzxpb.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2mwemplla.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2rkiwczny.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2slhbyrjy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2ikghizfo.html

Ruby: def to_s; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2pgwfqmqj.html

C#:   public override string ToString() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bewpslei.html

[G13] 判断对象类型
来源：http://dali.hfpthk.cn/Article/details/gt2chjuorfb.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2heiwqcqv.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2hbpnrxbm.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2hpmvogao.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2ujuqzeiy.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2sxwiffhi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gt2gstzwrnu.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gt2fysnvaul.html

C#:   u is User
来源：http://dali.yj202588.top/Article/details/gt2fuunaxjr.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqdhwjck.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbmaffbj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gt2wrzgjchf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gt2pxhaohwy.html


<!-- 参考信息 -->