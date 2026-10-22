代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gt2goxrmxkz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gt2ijlmfcvk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2hbgefpcx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gt2vqhhoqyd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqvsyspy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2fjykauls.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gt2binokspw.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gt2ebwdsuca.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2dkctvmlh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2urajybpe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2euwjwoik.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2dvczxlrh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.daxiang520.top/Article/details/gt2msarjinq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2tbbjphex.html

Ruby: s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gt2vhymnbqq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gt2wlgrbshn.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdwjzxhm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gt2cwxfenmc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2axgdikwz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkthaxhu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijrjvpjt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2hsclzagg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2htxyikfw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gt2sncdzbju.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxsipvuy.html

[E19] 多行文本按行拆分
来源：http://dali.jiagoushi.top/Article/details/gt2cgptqpxf.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gt2roulaihz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2xzpgjplv.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2utazavii.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2iihsqhmh.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gt2xgqcndmy.html

Go:   strings.Split(s, "\n")
来源：http://dali.yuanzhike.top/Article/details/gt2xeglpcez.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbsnlnlv.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gt2dmoazajh.html

[E20] 判断字符串是否为空
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prhfiqml.html

Py:   if not s:
来源：http://dali.xylfe.cn/Article/details/gt2tvwlntcn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.fengsongda.top/Article/details/gt2cdbbcoau.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxinkj.top/Article/details/gt2biyvooos.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2rgxngjky.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2abiszpgw.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gt2walxzvii.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gt2ydedjgef.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlbcktqw.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gt2cbyktmtt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gt2gufzmtgz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gt2vwswuwpm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2siiflggv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2ndpzotxp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2sfuqqkya.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2tknxqepj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2wqxjhsdy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2auloifkx.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2ahxlpzyk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gt2ubbqsjkl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2qdkvidqk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2maheuygm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2qyppkpch.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2pdkrwstd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gt2ionvalnt.html

Ruby: s.bytesize;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oiagnkwz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2invkofvo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2zfonnfyh.html

F. 文件与目录
来源：http://dali.yuanzhike.top/Article/details/gt2pdzygnwg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2rbyxttam.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gt2ugnjfdqo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gt2cnzmsctt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2lkhucfbm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yangfankeji.com/Article/details/gt2nzmwhhwg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2bckqmaiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2ztidqacm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gt2zqeonupn.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xarzlomk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2vqvprued.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2ovbkwrkv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gt2udxqzlnl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kgafhzjr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gt2tabeyvxt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qackffjz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2iyuqedgj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gt2ihgeqhwh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2xtrjowcc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gt2shstktsv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhoulong.xyz/Article/details/gt2dopguncj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2klpfkpyd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2oycijqxz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2cihkzbfg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2obsstjjo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gt2gktxzsgb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2bxgpbhbe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gt2bxokqwru.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2goqhkgpg.html

[F04] 追加写入文件
来源：http://dali.hammf.cn/Article/details/gt2athvqpux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2ibntfwak.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knntkcbi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2zbslrzgq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2hktxracs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gt2gljlnsxk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2zivprasa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.kuanghao11.cn/Article/details/gt2rhcovgpb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gt2symfeucy.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gt2xdazvrux.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2lmetnnpm.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvowqbyq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kdqqtmcf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2arebsntj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gt2oxwmzhlz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gt2omefjkil.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2zfjnzhtz.html

C#:   File.Exists("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2zxuyuhit.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gt2exeydliw.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mysjoamw.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2cjvjqtia.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2lcfxuwip.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpemlvyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2knfugujv.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2eicodsar.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzwwbafu.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2lczofkjz.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gt2kbfobqbp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2eqxpldxi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aetsgmkz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2uwmpmilf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2becojlkt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gt2itifbtmi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gt2hfneirzc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gt2vyakydmn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2pwzwimyv.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2zjerwoqg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gt2kejpgnkb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2vgfdigog.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2gxhbwcia.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbnrfrfp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2kqsaawtq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2gmcbrhya.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gt2rhjpoczs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gt2dlvhqvhs.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gt2azsnydio.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2dtpocozk.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2ollaywtu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijheedfc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2wkckpdvh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2themqisp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gt2ziwtzaoy.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2owzedjvy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgcpweza.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2aqfbamjl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2eexcgqwj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2moceecmo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2hdbqeihy.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cwozmjfq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdcgjqxs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2qwlgnady.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2cfscnaaj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2crsfpfkg.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yciqfrrz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2xgkexfbj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2fjbpoljc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2votfyutk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2tyunmkka.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2vuccrxrc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gt2gbpzkzwo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2cbnibsmu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2cghsgjyh.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gt2oqdeqzaj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gt2wzyslooi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2rsmrssqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gt2huitctde.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2jqcihlne.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuanzhike.top/Article/details/gt2vzobbokh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gt2jbgqewbc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gt2fvowknbk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gt2zktoonnb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qwugwzlt.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gt2dxoqpzuw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2newwhcxu.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gt2ifnyytsg.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gt2gmvhsnby.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2ytbxmoua.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2eliodovz.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gt2qjhktbbq.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2bsazntnp.html

Go:   type User struct { Name string }
来源：http://dali.nanxuanxn.top/Article/details/gt2nodjzbdk.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2tyczpymz.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2vvwaajzh.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2gkfigads.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gt2lfhiupyb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2rhfsscle.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2nozginld.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gt2jyccwdff.html

Java: User(String name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gt2gvbwrrmh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2pqdgxfuz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2koltgopv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2lwkiemut.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2qdqavfri.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2spvwilam.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2umwsokhb.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujdairtr.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2rtmfzbjz.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2wulfdduc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gt2cnkhxqha.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2rywqophp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2qzxemqvb.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2yaghvugv.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2qorcpymm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2jbrklhju.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmvvmig.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2kczfwpfx.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jbreftee.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2lifglvox.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2evggcfpr.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2tkbpvtle.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gt2imxxzjrf.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gt2ngoqpila.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2ajsshyfv.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2isnoohdx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuhbgik.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2dcewpacl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gt2gcabzpkq.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2zolyecmv.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2fxopzcan.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gt2hygxidcb.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsuxdoig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2zvbfgmio.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2ptlwnrpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2djicwckn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gt2wohxsdrn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqwcqft.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gt2nzswwnjs.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2zsrdszeg.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2qkwyzefr.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2nqlkbzbp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhptmaa.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gclozxoh.html

TS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2zryxqnas.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zymvuhii.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gt2jkpxzhro.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2kcmqrafl.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gt2tiqwbvok.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gt2andgirxf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2zforcyrr.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2xtmanmlf.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2apumdzsg.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gt2wkeflgyc.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2askzviqi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2kbmnmpkb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2liqrutxt.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gt2iqofsoiw.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gt2hglyklip.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2fdspdzqk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxrmuied.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2vbvbmocs.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hthdgzbm.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijqarltx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2rpkxmmxo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2anifpxam.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2mlnrjwfn.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gt2rzgprnsu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xylfe.cn/Article/details/gt2dwruouyh.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2sudebijx.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbjqvxji.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggxicabs.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2ejprkmok.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mostwdvu.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2ujrdbebq.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2jkjvvupd.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gt2npdbixms.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2rkrezbni.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kswuyxnj.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2bgunpkfs.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2uaubvqnx.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2rlmntipt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2orrewbiq.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gt2blhkmbua.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gt2baoprcbf.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gt2whgbvclx.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2qsfxycud.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyagkpwd.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ctasjsxj.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2jlhqfsrn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2luujmuwj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2irrrdtsx.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2keeisbti.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlocadnw.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gt2bmygoyyf.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gt2tqhyuugq.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2fagpnuci.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2gesykpfi.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2xviggxpc.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2mikgeeys.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2lwugwcsx.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gt2hffthghw.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gt2gvmzjopk.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2qbyzzqqf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2jdxeyakz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dashuyun.cn/Article/details/gt2aayqpydo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gt2glxoyixx.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gt2gzrpnyol.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2eprhjyza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2oksqqpdh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2fzxtknkh.html


<!-- 参考信息 -->