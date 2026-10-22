代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gtmktobtsk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gtmqidbxqc.html

[E16] 数字千分位
来源：http://dali.nanxinkj.top/Article/details/gtqgmxibnp.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gthgdcwzvv.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtkqypsboh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gtweuhlkgr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gttbucfzus.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtmiclsflq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gtjziunzhi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ehwqpu.com/Article/details/gtibmkvgmz.html

C#:   1234567.ToString("N0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfjceihy.html

[E17] 首字母大写
来源：http://dali.andypj.xyz/Article/details/gtvjagqeye.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtrgusxeyr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtdizpqoed.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gtrxfbdkan.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtidprdvqm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.0kj1m.cn/Article/details/gttqyfqdux.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ivvv.top/Article/details/gtoebvvlaz.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxnkhgxi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tianlin.xyz/Article/details/gturbfwpyt.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gttecxjihe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xinyue.icu/Article/details/gtdiysvfzr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtspbqwkhx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtuqxvasud.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gttkqaielz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtsxargkyv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtbgqmurtc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkdzzoajf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gtshjtcqdl.html

[E19] 多行文本按行拆分
来源：http://dali.ydzc1.top/Article/details/gtgxmhsjar.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtqrtfbadf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cdnleiting.top/Article/details/gtaugunyan.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtkyxwrubt.html

TS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtcxurzbpz.html

Java: s.lines().toList()
来源：http://dali.ybcxt.top/Article/details/gtbnahiyhd.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtpuiqcxpp.html

Ruby: s.lines
来源：http://dali.hammf.cn/Article/details/gtvjdqkvyg.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtxbdarazs.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtlwdjrqyb.html

Py:   if not s:
来源：http://dali.gotoacloud.top/Article/details/gtlxbmymkh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.meibo888.top/Article/details/gtyxarxrgu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gzhubu.top/Article/details/gtmazaxnfg.html

TS:   if (s === "") {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjmsoubo.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtqxflzgqf.html

Go:   if s == "" {}
来源：http://dali.quarkkingdee.top/Article/details/gtnppwlvhk.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtayjmlgnf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtiuzxsbvv.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtkzzyzvfn.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hywenlv.cn/Article/details/gtnpyxksya.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtpsdmrqbz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gtdxiczbeo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtnkehtcrk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtopigqjun.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtqftwjnzd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gtgejjrnaa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtfhxqttab.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtnszdrmgz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkzjjpeg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gttagtyxdk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtybrwjqov.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtijjyshyq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtwrferpyu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gtjelgvzgr.html

Ruby: s.bytesize;  s.length
来源：http://dali.sysykeji.top/Article/details/gtsvmtwwzn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtohdbkhkw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdfthdfbz.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytespvak.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkuvgopgn.html

[F01] 读取整个文件
来源：http://dali.zdqjudy.top/Article/details/gtxjrotelx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtzgrrghia.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtubinwbzn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gtbafafrne.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtutqlsqmr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtdrxigqzw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtqndyuaqn.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtmdtyqckw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtymdyfyav.html

[F02] 逐行读取文件
来源：http://dali.xziqi.cn/Article/details/gtqhknmxtp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtebristcl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwjgneth.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrjpzyspc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtuepucuwn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gttuheuyks.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtfityhvan.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yongpay.top/Article/details/gtrbihdxwg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gttottyxht.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtvqcdbvcd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtanowxnrl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtdppbrvhg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtsuhyavnj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtpmzkmejm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtyqozitnj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gtoqfxblgx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyfimikn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwqtvufc.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtjxbdfmcn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtzyybrivm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtqjynmagz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtviabcowh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtscowbmqv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtonzgbzhg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gtfhtywvyl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtulcqcodd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtiqasqcpb.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtehtgkjoa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtlsdkeuez.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtxewhbkpm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtocoyswzn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gthbxuofga.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtedtgncdr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gtuivtwvix.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtijebcqsn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdulqmdzy.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gtxddxyuon.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtbtweqehe.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtgrnzdmks.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpxaaunbp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthyxmtlcq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gttbmoetxr.html

Go:   os.Remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtkzfkbkzj.html

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtzyrmbrdc.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gteegytjkf.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtfyhisjud.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtgkdliuej.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtnaiwyexp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gtoeqvnyqn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtphjoqgjk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtwrfkauaq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtmlyacjuu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gtbudugmkz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gtmjdwqugz.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtqsiflecx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gtxhgmyxiu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtmompfskz.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtxlwscasi.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtpdyeyube.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtlbjlcflg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtahpkaglw.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtclpkuiux.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtuxsytmvd.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gtwgvrawxm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtepkknlfb.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtzjofvukf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtfaxmiwxl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtwefryjzq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtqlaewhum.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtzgfmeyhn.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gtzhrekhha.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltlfuiab.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aizwys.cn/Article/details/gtmydzqiks.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtpkhivjxa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gtmxnktasu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnmyvxouk.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtuwhkazhh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtwfscbdjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgcmmzymc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxltronfo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtapzfzetk.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtydgcojsl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkhybdcwf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtgugipajo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtocgsqopl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvojicrnr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtwzfijbjr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gtuvqcxvqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdcezuhhi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtjjnnjmqr.html

[F12] CSV 读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgohqtoay.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtzitkwnpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gtzmlbzbcs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtzapenmtn.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtqelkzfra.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtjwvlmkka.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbnnpqgx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtduaepjsk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtlxjcsmdh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtokjcszoh.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtxumwzfkx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtyivjeneo.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtyolpsgco.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtopmhsncl.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtvraxlkdu.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkipckek.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtcrvwtntg.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtgmznuawx.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrpwjlnj.html

Ruby: class User; end
来源：http://dali.svipenyu.cn/Article/details/gtfylzbhnz.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtmfzppxmz.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbjiioci.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtownqugcq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gttiwqyutg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtpfilfrzs.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfepzgywt.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gttcearpot.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtmvmdyige.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtpkubjvsk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtbhdwbakg.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gthfjngbeh.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtsajdoqde.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtblwcvipe.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtyctxyafb.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtshtnegjo.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gttlgfjcyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gthxcggunz.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtbnjfuswz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtephrdrwv.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gtafvisarv.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtfyndsiux.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtefkjwqxp.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqvthcek.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtrzmokdmt.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtthbbimcn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtiebjpawb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtoayrivgu.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtdyxogvke.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtpwmfopco.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gtthvvwucz.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtirtfxala.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gthizybplc.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtyvimxqma.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtqetphaqn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtwwfzrjnr.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtdioujwmd.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtenhytmir.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxrqvubl.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtxyhhrhcf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gthuaigvxe.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtueqpwlfx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtoaqjhvuo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtwcihazsw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiniqxut.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtqyjppuqd.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gttffdoioc.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtrzazhgzw.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtxnppvmel.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtmfbrciwr.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtzlgugfod.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtodunjopp.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtjtsxynwy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtmveoetju.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gtgxqpebgq.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtycernanp.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbyagfsm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtptkpctkr.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtnpyrxnnu.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtuflrbmyj.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtfsvekcng.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gthxnucqmh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtnlzxrxih.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtvmjkbaue.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gttqhxsmnk.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtardlelhr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshplmiyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtdovuszra.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtwyjsvvbq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtfwnxuqev.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtcbcfdoeh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtfzkwokll.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtgddvssht.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtpanodevp.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtvwzxjoij.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtdtdotufk.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtstfgvxpa.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtlrrgxjch.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtsbkxmxpm.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gtzbhcpkok.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtghkhpepb.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxkxzvqw.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtqdkncbmf.html

[G11] getter / setter
来源：http://dali.tanke756.top/Article/details/gtpxnukirl.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtojjuyadi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtjbnandbk.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtkbrjngdc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtauwjrikq.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtxwryxxtf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtyvxybpeb.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtkmtiguia.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtjhbedciv.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtkxpicdxr.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gteaauravt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtxoenxton.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gthydsshyz.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtzhfphsfd.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtsppwpkdg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtrkoacjjm.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtwuvwxxwn.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtfyiybhkz.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtkoftkcvk.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtffbfnyys.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtxmwiqgcr.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtcsyhjynm.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtgrtpibbt.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtofjrcyhz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtxxtexeqi.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtfstwztvu.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtozyputlb.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtdxvdpfuc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtsrxaqboi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtfwvztxwh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtynynwpar.html


<!-- 参考信息 -->