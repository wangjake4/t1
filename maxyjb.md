代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtkcmxvjyu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gtdnullfce.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tian-w.cn/Article/details/gthqzctebo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtcycuiwjo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gthsnldxgm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenzaomai.com/Article/details/gteynqregd.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtiucykvpd.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gttmkbbanx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gttiyfekoq.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhongyouzk.top/Article/details/gtdxdnrqwr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhoulong.xyz/Article/details/gtwtqxwpdk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtdxoobiae.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfcucvaeo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gtycmrbbuo.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtzquzdeul.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gtcwpeqvfm.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtahzpjujg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jqgufenzy.top/Article/details/gtbopvpbtv.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtabnenmdc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtyoimemam.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtyvlcpsms.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtqunjcwsr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtjkxjkycd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtdcgvsvuo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtvnxqqehk.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtnnfbpbis.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtatxjvojd.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtysbexiho.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtimfdfbda.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtzkalbaua.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtyvqlxxzz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtoebsjxkp.html

Ruby: s.lines
来源：http://dali.pycfn.com/Article/details/gtyadvcbro.html

C#:   s.Split('\n')
来源：http://dali.tian-w.cn/Article/details/gtpfroympr.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtrylsymsc.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtzslzuznx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gogol.net.cn/Article/details/gtdfylyhjo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gtcguorpgp.html

TS:   if (s === "") {}
来源：http://dali.yj20258.top/Article/details/gtixrqsnsv.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtfnwtukwq.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtltlznowc.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtgbupmhgb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gtupqeuxoq.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtkddqgcyl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gtrhzuatnu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtfwjowwhn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtcrbgcxyz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtgegrhcof.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtqdmndhak.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gogol.net.cn/Article/details/gtdyxiihta.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtajsoxsih.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtwujxzatl.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtnfexbwfo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258.top/Article/details/gtuvugdauf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gttkfwpkxo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gtdlukmdpm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangdashe.top/Article/details/gtcilhpkwj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtwntbhlyy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjgdxolx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtewrwjpkd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.havefunace.top/Article/details/gtavakhwjc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbdykqjyl.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gthjscghpe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtigptsikk.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtiwtfmpnk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvguqhmzf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtbydhxanq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258888.top/Article/details/gtvvhnpzog.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nwbrower.top/Article/details/gtgscdzout.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtgscxzbqk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtyogkfnfv.html

Ruby: File.read("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwfcilroc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gteefhzntg.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gtehhvassv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtahlloztg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.andypj.xyz/Article/details/gtjnylxbst.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fengsongda.top/Article/details/gtsxkjwohc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtvmcyhbcz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtkoaqkspp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.316326.xyz/Article/details/gtwbozqdce.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtrdcdlypy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.svipenyu.cn/Article/details/gtrzuldzmo.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtenmmnxpw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtapqsweon.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gttvkzwhuz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtzckgerxo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gthwrvbcvq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gtaxwibcev.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgsdrtqo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtpoondtgw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gtbwqmyolv.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtlbgfccff.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gthqloswyx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.birdmap.top/Article/details/gtsfrnlexi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtuenqfuyb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gttragnbtj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gtgkosqbij.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtoqqttzpf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkketexv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtvkkjrgan.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtlycyemdv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gttmwkqmei.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtxnfjsube.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjmjarfya.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtcwxcpgxt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtowscxuuc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hysaishi.cn/Article/details/gtnmfybhrt.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpmwzpspp.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgbkvowco.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfqwyoimi.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtkianyqjt.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlmmhuqw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtoweugbtm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdlupqbwe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtjfyybzhk.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtfendtlbc.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtskofxtyr.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtlkexbidy.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtzgfcuuvf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtgqgtqglr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzsdqfzp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtrqacpqcf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtpdwxyumd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtxsiqraod.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtmigiwrrm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtbjypgjft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtqgyfekij.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gthuscolzw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gtstjpecst.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gtocrfcarc.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtvanmattw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtfnhcrozm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtnlfceqlu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtqlashvht.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtjzzsozwc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtqotzzofp.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtjzjpenre.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxmrifqpl.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gtzogesvvw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtbrwtxqcr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gthzcuevzr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtglnuckci.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtghunbswm.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaqqizbo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtzbzhseko.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtydisqrft.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtxynkhnvr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimqywvht.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtvwosuybr.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoauxjvpu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gtrxzzcjsr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtdtoqyekd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwirfdbpg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtivttgzpp.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gthpkiwiss.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnakfcqaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtsiwgcpsf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtderwbsex.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlzsimjcs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtjitdfrap.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtaqukptqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gthhkbrght.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtcdgleqde.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtqiyzxowz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtoejngmzk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtvgorkjry.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtynftmnlc.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtoqlpizbr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gtfcmqewta.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtszdglxgv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtmfrbwsht.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtwkpniyyh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtefdtfjlq.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtmcmvssth.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gthudxfovm.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtaqsoimvx.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdiemhsxy.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gtelvuowkr.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtzddubiwx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtzmhhxyei.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gttztgdccm.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtvhdoenzj.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtinehpvok.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtelwbgrkw.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtodaqhvso.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtziqwjyfn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gtfvsfuynz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzpwezyfh.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gtlrokulyx.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtrlgxjiev.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtdkerlrju.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtguoxyovg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtswsvgxog.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtmfuotskz.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gthshuyzaw.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtlugylzpt.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtoccyvadj.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtfntyxuwi.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtoapldwye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gtzzqhimtg.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtwfjafnou.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gthogbfmdz.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtunsuttbd.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtekpvlykr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsxwbpth.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqmemieae.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxgwyupu.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtccjvqtyu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtvvqrxfns.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtapgjqcim.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtcfcexrjs.html

[G05] 继承
来源：http://dali.xuanzx.com/Article/details/gtclgixsgz.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gtshksyogw.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtwtxkacgd.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtcxhffezz.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtrzpetgfq.html

Java: class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtzrzpwseq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtmmclhuog.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvimmwrwd.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtadqffusa.html

[G06] 重写方法
来源：http://dali.ivvv.top/Article/details/gtzhezyvcm.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtlyngwiae.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtmkvwdxbz.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtysvaoydc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gthsockvfy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtmlpocnjl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gthjvfonsj.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtzhanojbd.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtvudsdmmj.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtffpihydh.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtdhscffrl.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtpimsqqgo.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtzeiiqbjq.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtihaegbcz.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gtykbhefrv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtkuqqedof.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhlgcnnx.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtkmxzfcqf.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtkzwammiv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtmshddtxd.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjcowidle.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtxpqlqgnb.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gttzlgfiqk.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtlvyjkvsq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtrwxkistd.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtwyezcydc.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtisgstbxm.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtjeztfavd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtmddgcfhb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtqnmbgwwb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gthhzevund.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtofcyirbu.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtckjencem.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtibnmizce.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtbdlicahz.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtxnugqawt.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtbwzbfcch.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtlytmsofs.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtemwxwqjt.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtdlyucxcq.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtjhcebyce.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtiivdgroj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtyicdqygo.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtmjsuahor.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtobrbvqtq.html

[G11] getter / setter
来源：http://dali.zdqjudy.top/Article/details/gtraikvhji.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtpokljqzy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqgbwgxtw.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtgwrpoysg.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtahjcmvgw.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtfwkuziza.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtzlcmbjlv.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtcrvwtfyw.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjjjujolz.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtxixidrws.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtldseshbl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtvrgqnduw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnaufuvpy.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtfitbdzbo.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtklycdlun.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gthlughenf.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gtbqmtyanw.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtbicpjday.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gtcsmuikle.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gtbmmxkhad.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtcadiewsr.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtzpackpqm.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtvyzuougv.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtrnpehzfj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtabcptcdi.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtvkzcckbr.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtpjchlprg.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjsnukmr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbxzkooi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtqacbmymt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gtrwazrpat.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtqwzxlabt.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtvigeobhh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtwzxrzxrf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtdpizgonb.html


<!-- 参考信息 -->