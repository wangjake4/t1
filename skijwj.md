代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtkklcagew.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtobdvvkph.html

C#:   1234567.ToString("N0")
来源：http://dali.nwbrower.top/Article/details/gtrdqhmfmk.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gtcayqyybi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.birdmap.top/Article/details/gtwzhwgaft.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtcestawtc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtiiilecys.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtrdfgoolw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gttkufaaeo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gtzqxjohoe.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrgfmwey.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtahciiuta.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gtumlbscfp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqpwuiby.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtdmzfkibq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtrxzfzmka.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxcjmdcn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gtlcpxjyha.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtufycytav.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnxiangtu.top/Article/details/gttqdmnjlk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtyshvilak.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtyeqygbpo.html

Py:   s.splitlines()
来源：http://dali.sxryk.cn/Article/details/gtqvvobots.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtttzjcjvq.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtjyzststy.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtuggcxbah.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gtbkukvtzn.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjkjjlvw.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtnicgynch.html

C#:   s.Split('\n')
来源：http://dali.ppjwa.cn/Article/details/gtbzhlrpkv.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gtfgsejgqs.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtvbdeszbz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gtuzwdhhel.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtvhseifpj.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtyojfhnvb.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtghqxewzs.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtwhlyruhs.html

Ruby: if s.empty?
来源：http://dali.ybcxt.top/Article/details/gtnspswlgf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtdrqoqywz.html

[E21] 超长截断加省略号
来源：http://dali.iojbl.cn/Article/details/gtjvbrtwej.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtywlathaq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgzpwbzm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcrlqgvx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtkpjwgfvk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtlzmyxxma.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sweek.top/Article/details/gtvuplfjez.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtksfmwdpg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtyownrcpb.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtochpmexq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtgoyrfxrf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtfygwkvnn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtrnfmoyjj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtgbfxwtfh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gtmltloumn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtnlkrrdmc.html

Ruby: s.bytesize;  s.length
来源：http://dali.smart0.xyz/Article/details/gtwfiuqawg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckjazfom.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmlqnussk.html

F. 文件与目录
来源：http://dali.gotoacloud.top/Article/details/gtdvswniuv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjfiykgno.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtwlijddxx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yueranfly.top/Article/details/gtgkqtsksb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtkwcpnntz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtamltbfsi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gttdhznyry.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtuuzfjolb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtbvsnevtp.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gttrsoudom.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtphhhtecc.html

[F02] 逐行读取文件
来源：http://dali.gzhubu.top/Article/details/gttteggpch.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsvdrdwu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtedrnwlvh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtoqodbjhl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtfgobjpex.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtqizbilyy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gtgwxnuhfi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtttcspgsz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtbditdwdo.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gtpeszwtza.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gttynqxjzp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtvmvhdfdg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtunuyrmjy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtozixlrdc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtecukgnab.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gthvkgcyiq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gteupuoxae.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtbjgbpduc.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtwpyvxlak.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtfzbwtanj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gtrnbnsoqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gtfjumfkly.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtybfailbr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtptocihvv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jianghu66.top/Article/details/gtqexmqvww.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gtwjaaerze.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtigqqtpbr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrvbqksb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.bjfxy.top/Article/details/gtcoieyoab.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtwasogyhq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtxtxmbnvd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtjavflsyz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtwmmxppja.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gtrqkftdlr.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtmgybcptk.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtiyuffrty.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtjlxjatpc.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtscfwaylv.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtwsiwkdgr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtebynuury.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtswsjzsnu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtsythadcf.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtslcelvtz.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfsyplsyv.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtbskttjmq.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtnufjhhux.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtbtlginap.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ybcxt.top/Article/details/gtyzcwwhrn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gteoblnrhx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gtiabjhdds.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtbitcazie.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtuxxijebv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtnwmluenz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gtwjnwpoog.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gttnvofhgw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtqoftmlqo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtqlwxgdpv.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrbiwuij.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtusciobbk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gtshbolpvl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gterfarrld.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtplcvjsgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtnjbefkqn.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtkdpgervl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtkifpywzx.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtddfjbmjv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtgaqcmznt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gtgotqdkka.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtedyocvtj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtjcikcgbc.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gtbnbfzxmj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtqjrsyduq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gogol.net.cn/Article/details/gtisgcjeiy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtazplgggd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtkfswzqli.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtfflpvrkj.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxqkbjpjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtzobetzgc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtulbeoqyj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipjoequq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkstnztxp.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gtehmkdwnj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtzfklzukk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yueranfly.top/Article/details/gtsrnsgdkr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtsjjfavlx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gthrqqckmh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtbqaeqyns.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtuqjlvrdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjiiaylv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtkjxksbdk.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtbepcyhhm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtrfihfcnk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtfslxfduu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtvzyqhdgp.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtlxuuefeu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fzhhl.top/Article/details/gtmcisytnb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtchtsjbdn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtatbdsnwc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlgxpmfn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzktuuetj.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtqtznuohy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiotlkoen.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtxrgtcpdz.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxafkovzl.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoijnycel.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtilycctwy.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtplbzdqwl.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtdcahnydc.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gtxnkqwivi.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtzjvbrvau.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfnkusgz.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gthusuhuio.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtahnvloif.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtrhuzpmuy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtufbudowq.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyyfatrnf.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtebbzwcaw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtzxuxbhjm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtvdygdhxv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtqdcgejrt.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gtxnopymmh.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtfuyacudy.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gtbbluuxbq.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gtgkxaezqp.html

TS:   name: string = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtbqoxakng.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtssjmauqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtdudmgyre.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgclhrioy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnrlhcme.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtnhgcrvio.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtwzklqyjl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtiixkmzqk.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtydvrfqwg.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtjehsjnby.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtanamvwkj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtmnisofrd.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjkspebno.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtoshrjfje.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gtlelnpvcd.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtqjhmdhrq.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtmuwnfnyj.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtymvxpsec.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtluqkcngd.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtquyfpsej.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gteuiocfgr.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtyhbfuutp.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtavpjfwfj.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gthlnotprw.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtglajlkey.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtkunmzvcs.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjoimruf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtivlgwkuy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gteitanwtx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gtqcjkviou.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gtzmplbrmu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtzezommxj.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtentaekfy.html

Py:   super().greet()
来源：http://dali.shzxlz.cn/Article/details/gtcvgjncio.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gtkrntzguz.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gthdnbasqn.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtvgibairy.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtiwmeywue.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtifxetqgk.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtkxurdiou.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtttwskjfu.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtbhxexosp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gtburimeel.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gtwnydxfqm.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtfvarkwht.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouksbyju.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtoxovuomt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtppftaiim.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtyznitrzi.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtkookhklh.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gtafkadeow.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtseekffgp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtctgqjsxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtrumgtaxe.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtlkdpznwl.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gthidarbln.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtleeunrlc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtszczzrhz.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gtstpfgcmk.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtoggqnazd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gttvlwbivu.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gtnnancsqj.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtvsaegufy.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtuddaiqzl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhiwuduotai.top/Article/details/gtesowmgvq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gtopxzyuvq.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdkazyza.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtmperlgpl.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gtyrshlllw.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtrxphdkee.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtnkcbryju.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxstlptzl.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbjrxyipq.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtnyqagbhn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gturgpixlo.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtcmfyuqyj.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtvbwoospg.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gtcpejyzgo.html

Py:   def __str__(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtbbazvrmo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtzelzqdhk.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtxxorqhhx.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtuoitgfmj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtwcdqnohw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtqcskquaq.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtudednffq.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtpwfzymym.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtsjiakiqg.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gtlnlpbawt.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtvcxse.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gthxnyktvv.html

TS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtybxtechc.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtqgnobuls.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guannengcc.top/Article/details/gtdmunzotk.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtkbibuymf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtvtjetgdt.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gtvkkjndau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtkjkvjidx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtpwwticmt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtkhhrnqri.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtrjsplcaf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gtmlqugxhg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gteoboducj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gtfdmywkxt.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtsaaskbwa.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtzjljwhfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gthsbpirfl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtwjejsvgh.html


<!-- 参考信息 -->