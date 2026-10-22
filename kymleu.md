代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtefnutwwc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtecgdznsq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yanxiufei.cn/Article/details/gtuipxzfhp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gthjqvlbjj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtprpnxrwj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtmjerncqg.html

C#:   1234567.ToString("N0")
来源：http://dali.xuanzx.com/Article/details/gtooxttlum.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtytjgxwwc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtrjxnwhsb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtpmzoulzu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtccmwdqwl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gteahdwqid.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.meibo888.top/Article/details/gtvqwtmbah.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtkvsqwgqc.html

Ruby: s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtdpthkaop.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.c1oappe.top/Article/details/gtyjprgzmn.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtgbvqavqb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tian-w.cn/Article/details/gtmjsykpaq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxinkj.top/Article/details/gtahraoiay.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtidnzzyql.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtxmwylhqd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtmjnhgyzp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtuggjgdoy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dashuyun.cn/Article/details/gtgifpmhzs.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtdvwhtuvx.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gtyrqcptmb.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtvllhflpo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtlnssopwa.html

JS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtzluohvag.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj202588.top/Article/details/gtfuocnbno.html

Java: s.lines().toList()
来源：http://dali.hnqzz.top/Article/details/gtuynxbbqy.html

Go:   strings.Split(s, "\n")
来源：http://dali.quarkkingdee.top/Article/details/gtgtmhiqot.html

Ruby: s.lines
来源：http://dali.tanke756.top/Article/details/gtexbvneoh.html

C#:   s.Split('\n')
来源：http://dali.zhengqikj.top/Article/details/gtejnnzibn.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtkdziwhpp.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtmikrwncw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.316326.xyz/Article/details/gteclqohow.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gttzbcjwvm.html

TS:   if (s === "") {}
来源：http://dali.jqgufenzy.top/Article/details/gtdvvtbvlw.html

Java: if (s.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtvrzvzryl.html

Go:   if s == "" {}
来源：http://dali.gzhubu.top/Article/details/gtlentcczp.html

Ruby: if s.empty?
来源：http://dali.smart0.xyz/Article/details/gtfdymfeqw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtmozbatil.html

[E21] 超长截断加省略号
来源：http://dali.shzxlz.cn/Article/details/gtkgqhgqvb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gtbeidhhvf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtdfqwrxdv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gteeddwkkx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gttaybkgaw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtxipssfla.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtidsrmgsx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gtptjulxsw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtcajtvexf.html

[E22] 字节长度与字符长度
来源：http://dali.yongpay.top/Article/details/gtrnjihljp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gtrupytswi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gttywptxjp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtsoqnwkwr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtxydsgmta.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtovhrkedb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gtiejitjai.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtesgoenbc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cucudq.cn/Article/details/gtuloioskt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtalhulhbe.html

F. 文件与目录
来源：http://dali.zhixingplan.top/Article/details/gtmlxrzbkj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtkfazhbcj.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gteislkhyy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gtaplfpoik.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtirgwqqes.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrbistvx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtanofctiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtrpxngydq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gtovqkmitv.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtddquvumy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hammf.cn/Article/details/gtopbvzbty.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gtatpzkhff.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtgbvhfjag.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gtuqeuzboa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkdutcwtj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtssqnsjvi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gttrhdczui.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.meibo888.top/Article/details/gtswukyqzx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtdcnydcyk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsokvzujy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtvkqynmrs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtppcazlbu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtwcojpueh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gthpghlhlx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtqzddvgzb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaxgqwvm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guowangkeji.top/Article/details/gttdupkqnm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtjugwqhtq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtpcnrilug.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtqlsunlzq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtmpsfruwd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtjhqtwgzv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtgssocuyk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtmnovpkvd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gthhviizod.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gtxnwvqext.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtzqveczcb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtealqjcqk.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gttohdvypi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtenbctkfc.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtfozibdie.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqfaisevp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtjaopzbil.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gthfnbglsp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gtjbhozsal.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtyurubpud.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtelbvhnim.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtzximyuqz.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmfuspckb.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtoppeprpz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtekqdnlzz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjzzgqetw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtjwbibjmz.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtaftvkyyh.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtvuyyvmxj.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtinjyqjyq.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtevzwyrbj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtykurbbqn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtqzynmjkr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtrpbntcqc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtfecxycap.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtkxwmfyjb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtynbycciz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtklrhbcev.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtqonauxpa.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtncrnddbv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtbjwbqikk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtygeinymj.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtcdwkdeps.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtblaowrll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gtiqambktb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtkujbkfzf.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtednqncgy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtctktvraj.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtvceqjrln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtuakwnnci.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtyocbpktk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtcyhiwfpk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gteepphcai.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtfljfdfcz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hysaishi.cn/Article/details/gtazgulenc.html

Ruby: File.size("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwwydyvfk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtydztiuth.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtwjeklsaj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtisbbuwri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtnsmjdhfc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxhwgppzd.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtpjyqtuou.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtnybhobfj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtgbsegvfs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvrkywbhd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjkxrjyax.html

[F11] 复制与移动文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfsvogqn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtyvlaxoby.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtujdideta.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvekppufs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtmlgznmwg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gthtqldrkp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjikrbtev.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtmkqjqova.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtfcwreswq.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtoppceumy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gtafgppvsl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gttthvsapt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtrrojtzxq.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtzdnisepg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gttjpyfpgj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gtzhbddzjx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gttxllesmo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtcnwglkgp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoorlpenf.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtiftiootq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcdlajizh.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtpsvubfwy.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtnmyqvthz.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtjjlrucho.html

JS:   class User {}
来源：http://dali.yonumen.top/Article/details/gtugebadsw.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtafjujivn.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvsfremyb.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtwvmvbkaz.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtwbfdvvyl.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzmspxws.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsdpwjne.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtcwzuqzzj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtjeaiyjnx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtzwuphiht.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtuxuinvax.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtxmldqoke.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtjrmfican.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtjdrtidxa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtayophpaj.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtxjqzlnwr.html

Py:   self.name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gthlybojov.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtplvwxkae.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtumyopooh.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtawrnrlht.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtqhzcxuow.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gteofmdtzy.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gtxpoxwiso.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtppkjruli.html

[G04] 定义方法
来源：http://dali.iojbl.cn/Article/details/gtbtfqjnfd.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtwzizrgqh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtxpztfpbx.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtbccdencn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjcgrseqi.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtcehcibul.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtfnprfpip.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtxalxawib.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtoocqtaxy.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtwqgrxrxt.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyopckif.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtzlhexuuv.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnlogvhke.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtillpcexg.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtccvprngj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtppioarow.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtieglgmaa.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnjvbymo.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtnonvwlhy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gteirjqhjp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtffeqzmyd.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtklslwpqs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtwdibbpid.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtnsqbktfo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtdlhmtdgr.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtzlqspqls.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gtoqawjmbw.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gtjeoyjygd.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gtcsigbysj.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gthoeihqkh.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtyaahmkka.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtxtehutri.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtbvircamo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gthtczerht.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtwhesvwmm.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtpmagfrho.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtovjrqhbq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gtkmflbwwi.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtaywhqeqc.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmhgamsy.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtyppkkvbg.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtjleqzhtm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtecirgzxb.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gtugbptkyj.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gtorsburty.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtnemhfcpn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtlbuifhuw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtspajyceh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtmwnmcquq.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxuanxn.top/Article/details/gtlnhjtzpp.html

Java: interface Shape { double area(); }
来源：http://dali.sxryk.cn/Article/details/gtwyebxiof.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtishvbfbf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gtomocwlwi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtqpkvlslm.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtbuvxeugt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtayvfikiw.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtwhquuzqe.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gtbpqkeiyl.html

TS:   public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtqexazfqr.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gthiehzdke.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtonchftae.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtbzydwfds.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtyapkyngc.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtzutvszxd.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gtrkvuyndd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiozukvuu.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtjenhgpmr.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtclazxoup.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxunocfml.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gthqqdrier.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtbxzywqbh.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gthoptmsae.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtefxlqwuz.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtytvbjzit.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtyysbkwtv.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gthnbabumk.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gthbjzofrn.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlbvhitqq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtrtbwneuc.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtzgwfumqm.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtjoebuwkw.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gttcfrjskv.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtqzutkspn.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gttjjhdxdb.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtpyquowzu.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgtdkljs.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtrnhzpcig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvoibwsg.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtvblctndi.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtxrzhlchm.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gteifiqghs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtmzrawszy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtmlfpvweb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtqrfxewmx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtpjojbvqu.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gtahyihrnz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtjzfxcjfc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtiqalwknn.html


<!-- 参考信息 -->