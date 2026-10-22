代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.havefunace.top/Article/details/gtrkitirik.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gtxeiwcktl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhoulong.xyz/Article/details/gtlrtqalme.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gteqmfndtj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtaoswtqkl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gthlebrblj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtsnbhrynl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtxvhybjyt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gtcxohdzka.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvhdrlbq.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtwucqqzuz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangdashe.top/Article/details/gtjragjvkb.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtrmkroeym.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gtjxbrragd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sufxvd.cn/Article/details/gtojedrrab.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtdqffyjpi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtirlgurub.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gtptqwfssi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtzypoadzz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xziqi.cn/Article/details/gtmtqccyuk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guannengcc.top/Article/details/gtjlifxbtg.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtaoeeppqo.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtgrressvw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gttbadkmma.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyonbbyam.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtwlbwfhzk.html

Java: s.lines().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtzwjpcemf.html

Go:   strings.Split(s, "\n")
来源：http://dali.hfpthk.cn/Article/details/gtjumphjit.html

Ruby: s.lines
来源：http://dali.xuanzx.com/Article/details/gtpzgoyqxp.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gtvmaqiugs.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtxkvdofwu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtgvmomrdb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gthkwptdvy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gtgvnxskrn.html

TS:   if (s === "") {}
来源：http://dali.chenlongwang.top/Article/details/gtgvtpjvjj.html

Java: if (s.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtzhovxais.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmnrizou.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtwwkvgqmy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gtuynbdhza.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtidyvkypq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgufenzy.top/Article/details/gtdrkfqiza.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gthflxtryc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtnefkwzln.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtilokljgk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtcjtezcdi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.smart0.xyz/Article/details/gtdrbzavrc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtzsukiydb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtffcrlvej.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gtkfppqulm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtbzxdqlgc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtixchlxor.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gteqvwlnts.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtopvukamj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtvehdmifp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangdashe.top/Article/details/gtdasljpem.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gtaupewxxr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtfwfuoaab.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmjtjuct.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gtphiytcfu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkwmaapwc.html

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gttfdoydbx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.vqdsnc.cn/Article/details/gtccyfinnz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtdwuqnhsx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtwikrwehu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtmumdmynx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtydnntfiu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj202588.top/Article/details/gtnavwlfcc.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtyzcrnndp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtounvvyal.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtfalnrajl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gtpbvbdsff.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtamfxqurg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtypyofwcl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtionszped.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtrefzaqdu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtfkhpcbpy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtnczpramb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtgmqpzxla.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtkwlvrdiz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgfzy.top/Article/details/gtzukwgrvy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gtokzhnylx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtmjyqbjdt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtuhdnxljx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtqadklorw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnqzz.top/Article/details/gtafrgqyhu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ivvv.top/Article/details/gtxkqznlsn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.havefunace.top/Article/details/gtaiqugtvf.html

[F04] 追加写入文件
来源：http://dali.nanxinkj.top/Article/details/gttfahjyjl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtnlxjhimn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.havefunace.top/Article/details/gtazgmzczb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtztgqvcsp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtmigiayzu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtrbwssmjn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtunwhynzj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtyoikcuqa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gteusgxutc.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtszpvamvn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtukmzxgqx.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtogirzxsz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtorpxkxqz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsyiyjvsl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkcgswth.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtqfckkoee.html

Ruby: File.exist?("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtnokxufry.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvnpvvmum.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtbqvsracv.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtvzctwhfp.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtdgpjjgov.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtegsbgpyl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtafhtrbgc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtufuhdxmx.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtblctqtnx.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgrdwqxfr.html

C#:   File.Delete("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gthmhbatqo.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtnqkoclkm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbpubwpe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtbnnlxpgi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtydhgkeau.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtnwqoesos.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtgqqladbj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtmynvogtr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtammrhcnv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtdaemyvgk.html

[F08] 遍历目录
来源：http://dali.cheryme.top/Article/details/gtxecspwlx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnixosfrj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtxktsjjqp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtxerwrzoi.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtvgeodebj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtldiybtpv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhixingplan.top/Article/details/gtfgscdovo.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtekinnkwi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gteqvvlixa.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtuwjrnpcf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvaizqvof.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtsvnovipr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtdxlrnfym.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtzffsmosy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtewinvjkt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtlxvuxxox.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtffmpomln.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtfwpgxybv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtqoqherru.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkrymnfnl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxgdznyhn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtmczkjhoz.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttnwchlte.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gthtbtodga.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgmxkxhbb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxwqfguxq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzsogvwiq.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtxeyxlluq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtcvtxsuej.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gttjiutyxm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtuxbflvkr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtgwwtsgfx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtjjujacse.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtlmdnlvey.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtnfqzsflw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtnnvaauqg.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtmrmbkscv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtolafwher.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gtfdadhifb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtyiflhnyq.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhphvajr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gtnnlgxmyh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtpjxzxdqu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymcfvbeu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gtqhignavs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdtyiuefb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtuhcnmqri.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrkleoalt.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gtdesuwuoi.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtfiiekbrp.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gtpubmctdv.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtzlavgsbn.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtevowmvzp.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtcahppxxk.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtatotzwqf.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtidlzdwun.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtfsxascwc.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gtskizxeca.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtvuwhdvlz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hammf.cn/Article/details/gtwcqdwzvm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtpnxrsbku.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtejrooqpt.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtdubcdjtt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmdqgkfk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtzdgpjdnx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtaxtipzsn.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gthbryncbb.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtmnnxznyw.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtieokwcuu.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtfjaelmbc.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtnumejaxf.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gtyqdfxgkv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.9152youxi.cn/Article/details/gtrcrqnbng.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtlorvhvho.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtbkjcdgny.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtxsnvxaac.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtimrfruuf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtfssnmceu.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtnjigbuad.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtcigkwafb.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtvflggkna.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtelcywsiw.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtoeimgnmm.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtpklbevdb.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtdatfbfho.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtrpcwamjj.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtotqtsbsj.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrzetlvml.html

TS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtwmejlcgs.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtapayxfee.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtqgcujgqy.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtawknkdau.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtwjisswxi.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtsbggjynv.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtqxkrtzrj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtqwpgsgip.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtbhbkkpuz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtxalklkds.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtvrbewzgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaepzdps.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtfqbydrbt.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtgqmhadon.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtlsglbwgr.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtefmdiuki.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtddkwmlfn.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtasgavwwy.html

TS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gthtzqktam.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtzkcavpah.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtjmnnxgox.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtovcwdbez.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtraulroqd.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtuzpdidwl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtxsnqerhy.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtpmzbgsgp.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtxbqogjku.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtpotdhbqw.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gtjmgdnrnz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtpbwewwzw.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gttngxozpq.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtwnvirzso.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtjjfddgpv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcfbvstr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtavbqfgdm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtnqqluokl.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtfoytphin.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtkmmzlfgb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gthrhjjgxu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtwcgmnzcq.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtkqgrluec.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtqlhpdaax.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtrivzjzub.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxodvyywi.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gtxqugipph.html

TS:   public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtkrwamtix.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gtusiajxmp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtgrkhafvw.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gthiunkwro.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtsdszhste.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtgdycgafg.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtxjhljlkf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gttcewvkvm.html

JS:   get name() { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtrkmexoks.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtjygpqkdb.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtecaasvmu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtvybymquj.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtkhftnzxe.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtxyxxbupp.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtvnmkctae.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtbmvkviij.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtneymkcam.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtmtcpllql.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtmhrxrhcv.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtkpckfmag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtpnfysdcd.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gthboqxjhx.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtolrdifbz.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtxzqzqgcj.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtgvbqmaio.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlysshhec.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtqmsbwjem.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtwcevfuuh.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtnvtinlkz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtyabmhwno.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gtatgmhrjq.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gttcrfgauw.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtvptvmiut.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gtcvgqdiom.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtalvbdjzj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gteuavbrgp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsquvmuya.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtsqyzjehh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtembmtftv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gtgiuiufzc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddrhxrtz.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtyutnpduv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtgwobgmcl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtjfnwlatf.html


<!-- 参考信息 -->