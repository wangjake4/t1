代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtyocvvlma.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtpuransby.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtbhcbgdot.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtgltugsbw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gtfwvnxyhf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtknfgqwhi.html

C#:   1234567.ToString("N0")
来源：http://dali.0kj1m.cn/Article/details/gtgrjgccnv.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gtkrncjmfi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gthbbifqgx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gtcexggpwf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtyzpcximj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsquinep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtaazhufdg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgufenzy.top/Article/details/gttoudtkpg.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtxngprkkp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cashguo.top/Article/details/gtyptuzhtm.html

[E18] 模板占位符替换
来源：http://dali.andypj.xyz/Article/details/gtzfhjlgvl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gaohongyu789.top/Article/details/gtekpglfbp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.dashuyun.cn/Article/details/gtymkyagof.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtdqhltdfm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtemefyods.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtcvlfpyhc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtppcbdgqr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtscjrqfnd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtkfofarky.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gtwyzkpldf.html

Py:   s.splitlines()
来源：http://dali.shzxlz.cn/Article/details/gtvisuxwse.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.svipenyu.cn/Article/details/gthgngnlrw.html

JS:   s.split(/\r?\n/)
来源：http://dali.dianchejie.cn/Article/details/gtahkuhzwy.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfskiyyz.html

Java: s.lines().toList()
来源：http://dali.cqqwz.cn/Article/details/gtcalabxvm.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtuuhmibtz.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gtjehzdann.html

C#:   s.Split('\n')
来源：http://dali.yuanzhike.top/Article/details/gtwrdxywlh.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtglnqjkvo.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gterhmknpz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtsxmetjiu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.svipenyu.cn/Article/details/gttpkrwzza.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gtjbbmmfet.html

Java: if (s.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtwugikmum.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtoowvyqjo.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtrupkzrsv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daxiang520.top/Article/details/gtjmgkmbuf.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gtojjcusdm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtyazdxnnj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtpzdivusf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtdlwcnaop.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtojinxzij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gteezburcj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guowangkeji.top/Article/details/gtwntizpmk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtnvzttnlr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gtjhazephn.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpubjrln.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtznlsfptw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtiagdzmwv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gthdllmobp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gtbdeqdbhz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtgewibhws.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkqxdcas.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gttyskrliy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sweek.top/Article/details/gtuxgkslax.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqczjdrjg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtnaexiygm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxvmvrto.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtywzdjtke.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dashuyun.cn/Article/details/gtdbnxhtsw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtujagkgxx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtjmiyymiy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.havefunace.top/Article/details/gtybpmaatf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtjxigpong.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gtzrspuqcl.html

Ruby: File.read("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtjhoqqbzh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtaerykgnw.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtnivpjhma.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihwrnnin.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtyhmpjojf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtkxcmqhlv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtvdlqdidr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxotasnl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnlklhii.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtorzdhiyq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtnhwophvm.html

[F03] 写入文件（覆盖）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwqzgoca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtouubweln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtllsqztfp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrgwvpkj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gthiayonoe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltzmftdi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxuanxn.top/Article/details/gtjpjnehit.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gtdxxpcpgy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtzczeirsp.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtywwfvael.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtdatdhlpb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtfnyhqqyb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtmxxeeusn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtibaaojjk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtyoglglhb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtlaydxlna.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shuidangran.top/Article/details/gtmvypgzqe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gtbrprfpgf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtpaomljze.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gtowcituth.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtsriaqcbr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtcijzesmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtirmfdqum.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtathxoijn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyinovohp.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gtojrxdqaa.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzhbumfri.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtauyhbusp.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtbluwvujn.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtnvhyyfjk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthdyewfzv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtroltoptv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtlvhyvjnc.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtjpouxtuc.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtepmtldcx.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtoxcrngai.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtfblbwoho.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtyffwtlgb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cheryme.top/Article/details/gtndbeqevx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtdvktkzpl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gthqdfrcof.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtdmdqcfln.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjwjucca.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtcsvgdeni.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gtrocipzrk.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gteprvmoxm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtqxmgwtki.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtanrsjbeh.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gthtdocdkf.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtooeswlwg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtajfzfnai.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gtagdmirzb.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gttgwocvhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtwoonlqie.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtzxesycsb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtczeyekjt.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gttteaqfaf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtqswpwdda.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtwjhuwcxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtscoxmxwn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtznaqjxzb.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkzvlqhep.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtbwxjeybb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtdcqaoowk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsxwxcyji.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtzkqexeha.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtzgsichug.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtysbfeyho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtfwtxhtok.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqsgbpndz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtfbfoiwqk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtjtfvmyqv.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtgumkpsai.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgjhyrkvw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgfzy.top/Article/details/gtwjolxpuk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxjzntvra.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gterwguuix.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtsnvfburu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgoiyxaq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfhfcdmej.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhiwuduotai.top/Article/details/gtgkhbxhbk.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gttigmaijy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtovscayni.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtzaudtwdm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtnwsfbqhi.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnphquinu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtddyaerui.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gtkukuruxr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtukivdels.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtulkxipjs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtihhgdjkk.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtvdpbbuwi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnorrrkvc.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtdhnbahtc.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtokphneik.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtwggfzidx.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtikveyqtx.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtztmbihnp.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtcqkgeuws.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtfqpuigxk.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtfjmvuwhm.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtyhcnjrni.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gtbfukxtgw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzieyfazv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzcatnxk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwozusxgp.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gthasxyhgj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtnktjcbbd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtxlgghtyc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjkudmeq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtbhyikpol.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtkjmhkwlb.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtxyfmeobh.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtjragqjza.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtkawokiww.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtfstxglsa.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtmrvpbwjl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gtvlyodfuk.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtbouzoodm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gtleycerfw.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtolpggyrb.html

Py:   def greet(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtolrewujm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtaofzuqly.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtuimhzdyk.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgrdrfhlb.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtsdljzdth.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtlplepyuc.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gtmngbcldm.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtfptekfuz.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtnbubjknc.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtyufpdmtv.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtkqxcqemu.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtmwwgkzjn.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtsdseoqle.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtlgygdoyp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gtrrlorlmr.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtqkrjxvqv.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtceurckad.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gtikbnesrn.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtehspevrg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtulozfsdj.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtzffpinwf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtchpjetxr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtjqypzulk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtozwwdsql.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtarqlnfln.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtxgauszds.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtynftzotc.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtsrgtsznc.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtbqwgrqtr.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtbjgxvqzc.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtoararjep.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gttflaxcnp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtednjxqke.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gthjdczadq.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gttxtjmhvc.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtrfzfybjm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gtxttfuxah.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtftwszevx.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtzcgqjazd.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtxvmbzaia.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtzrmlqsae.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtswyvjdhm.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtqzbqszop.html

C#:   public static void F() {}
来源：http://dali.gzhubu.top/Article/details/gtbagcrlym.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtxpiksafk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gtuxqvdqnb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gtihudauhe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtmfkdwlau.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtiogahkgo.html

Java: interface Shape { double area(); }
来源：http://dali.guowangkeji.top/Article/details/gtcixtumwq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtmaosiuqt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gtbnecjibe.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtbonpimme.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtnrnxkhdn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtwbouoiha.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtvfvnxzvr.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtdllonuqe.html

TS:   public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gttquiwhvi.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtdnfhaoae.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtnkrsbdhu.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtzvhluhtj.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtghtzguhx.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtahzycnlg.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gttjyimpde.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbnomqfr.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtlwtvwtcb.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtvvapirdr.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtlkeulotr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtuwavjkfa.html

Ruby: attr_accessor :name
来源：http://dali.jianghu66.top/Article/details/gtwwurtbss.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gtfevedfch.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtgosdzutl.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtcrmoojrm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtgadwsrnh.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtixyjspww.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtjwbrrzvt.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtkcxsbkae.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtyfqwwkqw.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtokwvlzac.html

C#:   public override string ToString() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehfxnqdk.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtfdtpquxu.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtgeonbiec.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtqzbtxddq.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtcfeylzea.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtihwngodk.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtnqhugzqt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gtxnmgpsfw.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gthatnmcjs.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtwwzvmtfv.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gthijkbopf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtnijuyaje.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangdashe.top/Article/details/gtdgxexjvp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtryfnmsdp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtpiirocrq.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbbowawl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.316326.xyz/Article/details/gtonyqvwdc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtfzhdoehr.html


<!-- 参考信息 -->