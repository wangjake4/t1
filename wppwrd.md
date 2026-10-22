代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.yj202588.top/Article/details/gtuocqybss.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gtrsdizgfp.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gthjmmwvka.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtjrfgibrq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtmxkrndai.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aizwys.cn/Article/details/gtlenfocmi.html

C#:   1234567.ToString("N0")
来源：http://dali.birdmap.top/Article/details/gtqhqvtdie.html

[E17] 首字母大写
来源：http://dali.jqgufenzy.top/Article/details/gtqznpyfjy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtzprgriif.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnxiangtu.top/Article/details/gtebivkrmz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtmvxkfbbb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtvtkqtfsy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtkajiyrgs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gtvmfxkavz.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtfbngmghv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sweek.top/Article/details/gtuefzehsg.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtlxgkdehw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtkpoueugd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yvedp.cn/Article/details/gtocgxjipg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtkgypiihj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtpahobzco.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gtbgcvwivf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xziqi.cn/Article/details/gtzhdlztsg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtraieiozh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenjidiqi.icu/Article/details/gtjkejkhux.html

[E19] 多行文本按行拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgdshxrr.html

Py:   s.splitlines()
来源：http://dali.yanxiufei.cn/Article/details/gtfoihwalg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cashguo.top/Article/details/gtctupykmv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtdqtkjmrp.html

TS:   s.split(/\r?\n/)
来源：http://dali.tianlin.xyz/Article/details/gtowoxhtxb.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtaavnemwi.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gterxwmmpv.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtlocvttjz.html

C#:   s.Split('\n')
来源：http://dali.hywenlv.cn/Article/details/gttcymhtla.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtwbyefrpe.html

Py:   if not s:
来源：http://dali.tanke756.top/Article/details/gtzabbcfaf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hysaishi.cn/Article/details/gtzcgshdoq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj202588.top/Article/details/gtjvkgaqkx.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gtmqprdtgd.html

Java: if (s.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwpgcfyo.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtoqcvqtaz.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtpjtmjjxj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gtpefagrcf.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gtjhytjoew.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gtjawvcdfh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gteqmidvus.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtvnjwynjd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtlwhpxktm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtzdnycwat.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtkwjhaivf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtpcvjgyvx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtzaanfmsa.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gtkvhzqpns.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtdllitbng.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtnjwcsvwn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtteqecfqq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtflpnripz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtvvmoprbj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtomaivqkp.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gthoshzlvb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtqvyuintg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtihuimozr.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtfabwkxqr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvknajgmj.html

[F01] 读取整个文件
来源：http://dali.9152youxi.cn/Article/details/gtzugcnbjc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gtduhnmpxn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtufthfsjt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqnhqsyr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gthbmegiil.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdgvlaam.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtnxxwafrl.html

Ruby: File.read("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqmrtjnuo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtltyzhfxg.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gtvxuyfrpj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gttufnxbgl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtfyrwssbg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gttkxzgjfb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtqwaljhrf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtfmeqethn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtpwraxvfj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtgsrtlehz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.redwolf501.top/Article/details/gtpqlpymtm.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtxmomkqnu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenlongwang.top/Article/details/gtmqsionmw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtsucujylm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtfajpfoxa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtbwqknhmk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gtwhbcocmj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqrumtrc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtsxrewnyd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtlmtxuhok.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtyyrqqlje.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtjbjcqhbz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gaohongyu789.top/Article/details/gtuscxohhi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtzfuswupv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gttmfmtebx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtthzruqbd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtbroukbtj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtkixepblx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtcsedlhbn.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gthmdaneys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtxnwgjsal.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtontxjbcb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthmkliofy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmgqihuoq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtwxmmcwzv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtjzachvhb.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtluejlelc.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxtwyahbm.html

[F06] 删除文件
来源：http://dali.hysaishi.cn/Article/details/gtcwkkqcwm.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmlleoaov.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtfsvzwveq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtceuzeexq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gthackomjf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmwdasms.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gtsejzczqh.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtdhiijuaf.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtqeqlhnqm.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtcnckbitq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtkflecxrs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtricpezkm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtepreowlt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtqjucgvul.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtkoynldcb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtojdxavce.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtayakefqn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtftpdiire.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtqxngcinj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigufen.top/Article/details/gtngbywwfo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtsxweaqtq.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtkdehsdeb.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtlbwldzdc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtuahahyyt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtgugjjdvr.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gtnevkkqls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvyagcme.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtrjexaoog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtlrncgyrh.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtxtkbohfe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gttoprzosq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtelrpewgm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtyykifpwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtcvykhdwj.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtepvcsmuw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gtiomnmnqf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gtwcrrbfjn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwqguneje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtamkhzzsk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gttfmxodvo.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtpqkycelr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtbokodiqo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtzzkllqhu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttmmuxbyt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gttwumawkm.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gthoncrrar.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtpauhiyod.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtnqyfxwyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtkmennimz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtctatmtfk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtxcwnkdsd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gtdyobbdmm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtbvajqozv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gtrtuhqylf.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gtcddvvtab.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtuhsctmhg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtictwskjf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gthcjdcrsl.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtbeztfynp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gtocgoufuq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gthxlisogb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtrhtcbgmx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtyitwrfqz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcnfpbdeg.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtxkvzllzk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyoyqkzxi.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwhcjhns.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtsjmofkfs.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtyekazbbt.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthfflssjv.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gttxvnkdde.html

Java: class User {}
来源：http://dali.aizwys.cn/Article/details/gtlasnpvfq.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtpuhurwek.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gtepggzbdg.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtmeuulezq.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtlxtrpfgx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gtvhyjcogv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtunlqmzeg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtatjhhydl.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtgvqyofem.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqjipmayh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gtgevqlwqg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gthdqqrrzw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtzyccdzrv.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtaplyvjsy.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtvpewkhif.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtxhhxfxgy.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtnrbojkcy.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtadyfhtnt.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtbuuvhgpn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtfahorbzp.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtqndvmglo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtndozydom.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtgnknamum.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtnvugfvzv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtkleuxlqx.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtsoyerscx.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtlbnipulg.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtfrangriq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtrllbxygo.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtpnbnhtyj.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtpgmamdiv.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfznhrhec.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gtusijmsph.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtuoyocixx.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjufijnnp.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejuzvosk.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gthrvofdsz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtahafanli.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtopkysfhu.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtuychliag.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtqeezsalg.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtrmaxgvbe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtweaevpxn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtyrgzhwfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwaqpmvhx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthojgmzxr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtcrsmzjri.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gtazuapbzm.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gtrhwouazt.html

[G07] 调用父类方法
来源：http://dali.9152youxi.cn/Article/details/gtqqdfeniv.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtryopppvb.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtrlxqfgte.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtqeiqlqwv.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gttbcdqsgr.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtitewbfdj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtsdouzgwy.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtkobnjmet.html

C#:   base.Greet();
来源：http://dali.hfpthk.cn/Article/details/gtmfndfycb.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtvotmyazb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtdenquamh.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtouyasppm.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtcdpmbdar.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtlfpihcyr.html

Java: static void f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtckqutbso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtpdzysvxo.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtbbklghae.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjffagzmi.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258.top/Article/details/gtybtpwzhm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtndeztkdr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtohhuucvf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtalswfdao.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gtqvufkkbb.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gtpyaiufcw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtfzhpjcaq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtrjxwteuh.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gtqyemyplt.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtltfqemyx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtvlacrwsi.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtcgeufdxi.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gtbygxvahz.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtgdvnqjqx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtggknbnoh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtlxuvooop.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtorsmyxvl.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtunotyeqc.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gtmejigsdf.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtewovzdlq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gttebvxykr.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtolmiujek.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtqayasnqs.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtteqwxfkg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtqmceablg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtwwxeogpy.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtxfnyqagv.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtovzqyhin.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gttmdlidmg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtggvtehic.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtngbivahx.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtuhrusvbb.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtebbduacm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtnnpsklws.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtynuvdvgt.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdimuahv.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtdbwqlpsu.html

Py:   isinstance(u, User)
来源：http://dali.dashuyun.cn/Article/details/gttojcbeva.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtcvchnbgv.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtvhnnvyra.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtzxcrgnyz.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtwcnrxqot.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtjftsuhts.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnizntgok.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtfpfissvn.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtyrmhhbbb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtqtqxtdwo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtihuhsghm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtlcvhrzrc.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtqwtdguow.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpoblmsgs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtnenswisb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtpoxkrksc.html


<!-- 参考信息 -->