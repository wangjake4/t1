代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gt2vqxtwvfq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2gavtkphv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2taktmvbn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gt2wfpfjgyk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qafeumqk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2sdlthrjh.html

C#:   1234567.ToString("N0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xamsqptb.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gt2llkusiaj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pycfn.com/Article/details/gt2cdqlyquf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvxraywf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2vgvkvdbd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2bzjymcje.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jitietbb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gt2gaicumjf.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkdgoprk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sufxvd.cn/Article/details/gt2hbyfbvcx.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gt2tovhjbtg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flcpwbzq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gt2zvnmwssk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2kwqnlxrk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2itllkgzg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2qhsbscmp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2yglorfky.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2tuitsdxc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ygyryrgp.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gt2tztkemes.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gt2zvnfllnf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2imhxvpej.html

JS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2doqsxnou.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gt2dhhfexmq.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2icxnjsli.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hpcdcohy.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2aehiwnqf.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2zezrxmay.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gt2heaghooc.html

Py:   if not s:
来源：http://dali.cdnleiting.top/Article/details/gt2djkwwtaf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gt2lrgbmqwg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gt2ncztxeuy.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kydetzlv.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2kvewhbeb.html

Go:   if s == "" {}
来源：http://dali.ivvv.top/Article/details/gt2fdwpzepy.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2exayrjmh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kzhgvvnn.html

[E21] 超长截断加省略号
来源：http://dali.sysykeji.top/Article/details/gt2pgsspngs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gt2czxmtbbc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2fuelxnig.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2vlbvqcdm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2kkcfkozz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2lgvzajah.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangshuangyany.cn/Article/details/gt2fbqeoetb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2mfvochbn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2vyblmlpv.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrzbohsq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gt2vfttybds.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2tkgvnumt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2yldgrnkl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gt2hvjgbbrt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gt2aiegraox.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2ehwnfflg.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2ykumvrgc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gt2wcnibzsz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2cdxmpeln.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gt2afpgonhb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jqsadayp.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ujptsoyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2firjtchr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2whdoyztm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2chkdvxct.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2niyqoini.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2dvwzcqyk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2xuqztjdy.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2pmsmvgiy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2gktfeuow.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2vckmdmur.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gt2qevssdcc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2hwjgugtc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2sucvnytp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2nzmwkngh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gt2xvkzmcbf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gt2vdhxfjdo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxuanxn.top/Article/details/gt2wshwzvhb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2dfddqnjs.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gt2yiwukxnv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gt2kaymusni.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2jygojsuj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2lnlwoyct.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2chtqwoql.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2rpjkiqoq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gt2bipywnat.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2naexwtmk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2zilqfoia.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2ivhtbdus.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2dhmgajnm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gt2ifflskgd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2wbuasvyu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2lccqmamk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zdqjudy.top/Article/details/gt2kkftaqkb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2aeyggpui.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2rudtppyg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2harpnhdr.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gt2yltxvqdk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gt2iytcyfyw.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2xzerajkg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhmlvriz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2pndxpatl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2iolgnmma.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2qdehzanl.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrulmaif.html

C#:   File.Exists("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2psjvpaxr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nefcmuhn.html

Py:   os.remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2gdkwfmcw.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2upmvxtuh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ksmqvabc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2aiwdbdak.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2lglwrtzi.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2hjvbzvpz.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2dfbsxewn.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2fniizshi.html

[F07] 创建目录（含多级）
来源：http://dali.jiagoushi.top/Article/details/gt2cbrgjftk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2ocfhhzoj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gt2rbnwmqbw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gt2sdvwzfom.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2jgcesgig.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gt2geurxsvg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2iueqcpig.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gt2fahktuwv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yueranfly.top/Article/details/gt2gwfbkvjj.html

[F08] 遍历目录
来源：http://dali.gaohongyu789.top/Article/details/gt2cslgutfx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gt2oqryerog.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2djzsaibr.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2tpxqiwjr.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2crekxzoq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2xuhldchd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2icljdssn.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gt2bwwjnsmv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2ixhchsfu.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gt2pmiibksc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2uvitlmoa.html

PHP:  filesize("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2kyezptcr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2smrbjumg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2ppevazfg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2twlmieot.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gt2quejgyfk.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lcpffopp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2pquxnumn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2oxysrfwj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2zvuqtgla.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2kyakinyb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2usletzzs.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ztjjfqzj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gt2sujytfkm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2vsvpggek.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2apjflynf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2sgnpferb.html

[F11] 复制与移动文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etlipuvn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2mjagbhyf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2uzsenlla.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ggnjhuza.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ponzpbzf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmgaiapu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2auexyacj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2atwavqkg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgfzy.top/Article/details/gt2cwthqefm.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxcotovp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gt2jkbvwqva.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gt2holoutur.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gt2ajzbelnx.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2typpwvva.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gt2kclmlolc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2gklxbmhs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2qompbkrp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gt2vnyjxhbn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fiakqxbt.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2wdnvqfwz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gjutjlbu.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2ixbdnvwe.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2sjdfjtmt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzufpfk.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2abpcyikj.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gt2aipetysn.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apvxvhvt.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gt2rvvryqap.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2adotayxd.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjeaanlq.html

[G02] 构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2plzkbgtu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2zhttjcvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2iogvvyzc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2gzllbfrd.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gt2spvhsucw.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2tvpxijht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2tqlfonlf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2halycrvw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2rhglorbb.html

[G03] 实例属性
来源：http://dali.tanke756.top/Article/details/gt2ecatluvp.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gt2jfjirral.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2slixvimx.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2bjvewoyo.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gt2uhleklzo.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gt2rwucjhhf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2knzhpheh.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2ogonuvgi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2jfqjpmml.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2hadjzkwp.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2yufkjbdw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2rrxbpciw.html

JS:   greet() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2dvlgihob.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vcoszfof.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2skwtudfi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2hdudewlh.html

Ruby: def greet; @name; end
来源：http://dali.tian-w.cn/Article/details/gt2kkmaaspe.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2jcwuqbmv.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gt2sgkjdvgu.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2ffbbxkzo.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2zxutdmjy.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2cqohnfol.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2cyywwhxq.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2odqchjtc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2irzoxchd.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2fzdryedj.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2fgdgnwyw.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2jdqehnoa.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gt2twoxlyjf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2wmvgzevn.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2otipzwpj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2oftwwigy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2yohpppbc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2znbgfdya.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2pytgdbep.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gt2djxwyhif.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gt2uijkarfi.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ecdpyktm.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2hviljmav.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2devmqszr.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2xehgtzhp.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gt2ycktguoc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkwdigat.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2tyutlouu.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2hrtvoikn.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2brfuklyu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gt2rgqoehgd.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2plqlvjga.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2dqscbvba.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2qohvkhdc.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gt2mwjmipvy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2zrsfnhvj.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gt2yahrbayj.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2wgbusatb.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gt2touixzpo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2fthwhuox.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2kkvuprwf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2nxxkrcly.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2lzyfqdzw.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gt2ssrpnnyh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2sxzarbal.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2xoksuyaw.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ymdbuvup.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2kkwhzjbk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2hdirvpjh.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2ofjsejne.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2jcnugtmm.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2yuwtkbbv.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2jffshpve.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gt2qmounzrg.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2moobsgoa.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2xivxjadr.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gt2whatovoh.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gt2piiffwta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ktgskwxq.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjyzboka.html

TS:   get name(): string { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2cvqemqbf.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2lqekpyga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2jvosuezx.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2dbmboeux.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2stygonkj.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gt2ezkustet.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2xoszngam.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2mkjvinqg.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2tabajgte.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pxmrvnha.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2yscmxbuo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2jhxznnxq.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiphmrtr.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2itmbputp.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2ubarwfxo.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2yxpbpvjx.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2syeqtzgo.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krogkrig.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2zolpcefn.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2xpcmikym.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2ybqlubgy.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gt2szuprjqi.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2wintrvrr.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2rnhbktyr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gt2akdnpixo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2wsgzxwez.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gt2usxetxla.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfscfbtl.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2lvntkwsj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2iljpoqji.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gt2iotkbrhr.html


<!-- 参考信息 -->