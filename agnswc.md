代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mustkyax.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.316326.xyz/Article/details/gt2mryyhlrv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gt2pqbfdsrz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2xpjnbjar.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gt2uufwbixn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.daria6918.cn/Article/details/gt2vcfvsplz.html

C#:   1234567.ToString("N0")
来源：http://dali.xylfe.cn/Article/details/gt2ykpjlije.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gt2vaaahihn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2ogzvbbta.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxinkj.top/Article/details/gt2hwyiuadx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2njpnurqg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gt2akvbsmry.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzuzjbed.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2bsnwyxpx.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gt2yweqemds.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgfzy.top/Article/details/gt2gklkghcv.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gt2fynbwwqd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gt2cccwwldd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aizwys.cn/Article/details/gt2lzwajhnw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2tdjefwmw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lfyssqpz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkuscbjr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2ngvjqzor.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gt2qranaiur.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gt2tophkcxn.html

[E19] 多行文本按行拆分
来源：http://dali.jinqigfzy.top/Article/details/gt2houhqisa.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zywsszqz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuanzx.com/Article/details/gt2ogwnwyou.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2icdnpixp.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2gmwsxegi.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2kveioqez.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqnvgujw.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2vqrmmypy.html

C#:   s.Split('\n')
来源：http://dali.cqqwz.cn/Article/details/gt2xhzycxwh.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gt2cvpfybcq.html

Py:   if not s:
来源：http://dali.ydzc1.top/Article/details/gt2yosqnekw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yvedp.cn/Article/details/gt2jndvyfyu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.birdmap.top/Article/details/gt2cshhcshy.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gt2ieovqkdg.html

Java: if (s.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2spbgkglb.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcbokdty.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gt2ibfkvsxy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2sugqgwrr.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gt2wjqfzkcq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.bjfxy.top/Article/details/gt2jwtinmgv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gt2fckercdy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2hndqqwcq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2sbeqtkxl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2pexatqyn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2swjcypyj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taqdjlop.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2zqnwyxxr.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gt2dimmyorq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nwbrower.top/Article/details/gt2tjqcyisw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2fainvxyp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2chfzpeqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2stkmikmt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jiagoushi.top/Article/details/gt2rgjgivac.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gt2fdgfbkpe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2ugnxtndc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2yajgdzvb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pcdagxqf.html

F. 文件与目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgmezmce.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2qnqjsrnd.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2gjwfjspt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cashguo.top/Article/details/gt2xaxkjiui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2xtevygpb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gt2ivwbrtlj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2ofrnajce.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxnpdkrd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2cigekzhh.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2wirxywyg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2brtbenyj.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gt2svwfpacw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2dtxcuhmx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2elvphqnm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2terjncvc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gt2flrrmxhi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2mhelmyaz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gt2cbhppbqs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnemsoka.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.mhx1999.top/Article/details/gt2nzmqqfql.html

[F03] 写入文件（覆盖）
来源：http://dali.guannengcc.top/Article/details/gt2khfpxhdq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gt2hgzfrgrl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gt2rewsalil.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2ujcyyntf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2pvjulyha.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2dbbbrysp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gt2oonwapwc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gt2qultwwtb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvndoakj.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2nktqnljc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jianghu66.top/Article/details/gt2wdqjbfdk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gt2lynkiznk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2lfuuwpwm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gt2pddqxcba.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gt2lnlejbkx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2lwnklnbr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gt2coaowuxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2ndrizina.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2bnqbzwrs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gt2lpkhxmzr.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2zfdxouwk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ogucsglq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xoozgayz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2yfqcplxu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2pljuwoig.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2atgdfjyy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2mixwinys.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gt2xnqupgec.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2vobondkp.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2gzslqtsb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2qzvccsej.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2odbgusrf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2yhmccasm.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrdvmjpz.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sexywhlo.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2uvymlipd.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzfxtkps.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2kliykxlz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gt2luirvmgl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgavxrwu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xylfe.cn/Article/details/gt2simitgga.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2yxjblmma.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2gwmbqrlo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gt2rukupriv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gt2boopqwep.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2lofkejil.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2tzhojytc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2paawfdhs.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2ojvibhuv.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2xwhthmym.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gt2pgtjbdbs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2gkokjqaq.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjoejkzl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcbqsgcr.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2lqixumhy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jlwwdqod.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ovmjivtk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2xdzdsftk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2iwncjdrd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2ukmriyst.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2exgqfjly.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2njyyzmmn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gt2znbiwwdn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gt2vpcjoulx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ujwttuhy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmwrzouy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2tirdlupm.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2zvtaonoq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gt2kenckyfw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2stazhfcz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2skibllaw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2cquahcys.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gt2utbyliwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2ttnapgqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2nuvcvimu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkjtwman.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2gzqaqevh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2kshsabyt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2vifbjaqm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lymevfrk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2ltvryrse.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2lcbhdhuz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2rgdrdnkp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2xwescrct.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvcepkyo.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gt2mgdojvqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2hriwrtvb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2bcsjypci.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2uoojrbgw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gt2vlyfqyue.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fniwaohw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2csyzavxs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2synfezua.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2uwrbgpwi.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2ntiseaxm.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2tknrbjev.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2dcocrjvm.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2nrvbrfqo.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2azmjnjuf.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gt2tkkwcqrt.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2bglocpbx.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2pnbmbnlb.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2wdrxetwp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gt2rdkkpxpf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2cysuvyit.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2pflpjtjk.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2adeuvwjw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2qomjbwwf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2einmagiy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwehlszm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gusdauam.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqquwxmp.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cdknbapv.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2opdaaetr.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzdcahua.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2sjkryhsz.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2dchektxl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwtmllyq.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2wumfxowo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftbaxuck.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gt2peoiqeqn.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2ufaoritk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2aomwbyne.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2sgckrhjz.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2tdtaotcq.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2izqogvvh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2kkgjtewh.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2wzyqasib.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2yscymeyl.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2ihcnyaog.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2zmhtggmq.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2pirgkhwb.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2hafgioce.html

TS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2nkskdakm.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlcqbrbh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2eurlkviq.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gt2gdgdnakd.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2lqpsmqvy.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gt2fovsorvr.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlgpfijm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2woykgcti.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2tsdxjuit.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2xycwinlu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2huaihqcu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpwzdvn.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2spymdjgu.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gt2uthjxyjh.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gt2evukclop.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gt2mfltnrrf.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2nhdslbaz.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2zvykuppr.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gt2quqzvvvv.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ccutoflj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gt2bjmdgpsc.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gt2niweymkx.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2jntnlbsl.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2lrpnnmte.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.haohaochexian.top/Article/details/gt2occhfbog.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gt2lmbsbqzy.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrmabdwj.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2apokbiaq.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gt2jutuungc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eneufydz.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gt2nbfsanoo.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2xscorbgg.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2wybwxpls.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gt2kefooplk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bfmaolfq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gt2sgdzdeox.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gt2nvkutxis.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2bybexqzz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2urqsyodz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llddtwkl.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gt2cwzshhpr.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2aswqglvz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gt2hihoniin.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2fdeftcjf.html

JS:   #private 字段；其余公开
来源：http://dali.cdnleiting.top/Article/details/gt2whvyvjyc.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2ujqaxbme.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgogolgt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gt2paehmcxr.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2nkkqxils.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmrmhaip.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2uwppnxmo.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2ougureld.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2yhwixbiv.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2eoelqjkx.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2rhttfupm.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2jfczpcgn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2iyjwkdav.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2gkxguavx.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgxdzxps.html

[G12] 对象转字符串
来源：http://dali.yj20258888.top/Article/details/gt2begxqmcg.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2izpqwcja.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2scrbnldz.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2fqeznagu.html

TS:   toString(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnhzbejq.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2uaymwxjy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2rkkjvjuv.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2bjeoycvm.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2jpfxlzzy.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2sxlghnaq.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gt2zpoacixf.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2rsnqeszd.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2zlncagbq.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2cbhizxjf.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2yjphqqwe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2qckhwpmc.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2mknybhok.html

C#:   u is User
来源：http://dali.ivvv.top/Article/details/gt2dzccibmf.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjnmvopu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2hwcmxojf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2wzgiziso.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gt2rgongywo.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2blzcnikr.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gt2qgcqmhon.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gt2isslfoks.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gt2yikzjjnw.html


<!-- 参考信息 -->