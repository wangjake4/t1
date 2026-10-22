代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtdduffiou.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtdwrfzsqh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzdzpxck.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtghofktdh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zdqjudy.top/Article/details/gtejguszbj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gtzgcjmhls.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtqgfkybak.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ybcxt.top/Article/details/gtzhrpdocq.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gtlctcgaum.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.birdmap.top/Article/details/gtewqxkrmd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gtxfntvyib.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplyxicag.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtzmcfbror.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gtsjhegbwf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtonsgeumb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzqohfnm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gtkfgmnond.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gtsrruexev.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gttwtrfivu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtaqzltmdv.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtogwbhghx.html

TS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtghyamtju.html

Java: s.lines().toList()
来源：http://dali.nanxinkj.top/Article/details/gtzubglymu.html

Go:   strings.Split(s, "\n")
来源：http://dali.cucudq.cn/Article/details/gtcckjczms.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gtcrdcgrjx.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtxgaagdqz.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gtdvhvxlfh.html

Py:   if not s:
来源：http://dali.yj20258.top/Article/details/gtxzyreniy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinqigfzy.top/Article/details/gtwmsaqkam.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtuwucdzwk.html

TS:   if (s === "") {}
来源：http://dali.gogol.net.cn/Article/details/gtipculadt.html

Java: if (s.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtkhrhgbox.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtffkeczrp.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtclpdheng.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjsvgjvvi.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gtkzzinvtq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtoqzlpaue.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtevfiyfpk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtpkghyful.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtmawnhnyx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtiacbksvm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtzfcjilbs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtcpcpozdj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtpqvhzaiz.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbpjszdf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtjboibejj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtnadewctu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtcsbjqgca.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gtriprkiny.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gtnftwbicj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtiqcviqqt.html

Ruby: s.bytesize;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtjydhvmdx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtsjabwnag.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuztgfiel.html

F. 文件与目录
来源：http://dali.xziqi.cn/Article/details/gtlxmziici.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcgndwkba.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtmrozpxxg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtlrnzujrh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtfciyiftp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.andypj.xyz/Article/details/gtbfltdipf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnvkhiuy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtojmqdwfw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtnxbhozsw.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdbzohpyu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gthzyakile.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtqmklyamp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fengsongda.top/Article/details/gtsvoyyumb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtzwjlpsqd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtjgcytjfs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtualrgkjq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtqxdozsgt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtvozdcslz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtlenftyby.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtnzybxzgi.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gtdcnvgind.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtedvciepj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtvjztyrpu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gthffasafj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gtrrzznsyb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtyumhmdze.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aizwys.cn/Article/details/gtpexeelgi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gtyulvkfuc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtsoioxpwv.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtkdgwkavo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtirixxplg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gtiwvxyxpk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtpkssyfff.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gtvkikcszz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtlazccsum.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtdyvtnqgo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtuscaejbr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gtpvczbsmz.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtmargjgpq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtedmqzouj.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtbpvhimpp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtjumrjhuw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqeqwxemm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtnsbesvws.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtxocpsswg.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtcvrckkxg.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjbjgqhs.html

[F06] 删除文件
来源：http://dali.redwolf501.top/Article/details/gtyzedybdi.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtoswrkymh.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtlotcqitv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtemmfyicg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtfwseenhs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtxdcuezrv.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtatjcpzlq.html

Ruby: File.delete("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtfvyvjplb.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtwspyxdsg.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gteeohusrf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtuygrmonq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gtwzaegbxc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gteapfrqhh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gtpybkpvcr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtehawfclr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtfacbbgdh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gtsxgpjnkq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtaaqnrdnm.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtdtijwafg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtslqdgprb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtqwzunsnd.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtsnbrifkz.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtpbvscohf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gthsbvmoam.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtogpizftf.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtdweakyrd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtjrydutgp.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gthpixhxok.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtuoxrpxtg.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtfuvxdqka.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtookiadrl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtsrikdoir.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtyhhjwbzi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtbbwgogdq.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqathnzge.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gthutoxoxz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtubvuhiac.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkzxlwooa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gteobdqmud.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwicjxoao.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsdwslstq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gtfqvsupvx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtpsewvbdi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlsrmdyiz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtebgdzeiv.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjdpywyuv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtammqswjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtvfcaienm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gttsusqhuy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmnnwqqjf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtmqqgxxvr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtzlbvbcwp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtaqdkfoyh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtqpgkpsor.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtymyysfev.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtexwqcmpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtyntbmwel.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtvohxtajk.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gtmgmnapnd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gttsolasfy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtgejmdwrj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtcyialkuz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xziqi.cn/Article/details/gtngnzvzkw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjycvoxsg.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtmgmjsoho.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyvxqilsg.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtuqmjwjty.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gtitqpgwts.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtjzahpdip.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtzjqmpfor.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtuzrjenrd.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gtdzsuxgff.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfgdafle.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtfxknnqul.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjneuhqsk.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsualymm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtsbdetrwj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtlrfoedyb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtwaorsaap.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtzlyfprgq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtcagrfgdk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtodwoshtb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gteumgzrqg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtklgewqxz.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtthxtvxoh.html

Py:   self.name = "x"
来源：http://dali.yonumen.top/Article/details/gtkiizzafx.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtustfzwfq.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtnkhzizbu.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtmwsvqenr.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gttxtbdyqa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtkxcadrky.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtsnxwkuks.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gthpljunte.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtsqnsntey.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gthxifnhkt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtfcwlnkta.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmlqnjhlu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxhhlrdx.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmxztivho.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtonjbvxpc.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gtdgjnxghc.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtvlzjhqng.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gtrfyzuedd.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtyewyyati.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtcdnptpwk.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gthyoelkab.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdxypihni.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gthsyeehpk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtrezffwps.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtxpviibta.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtunwpvhgg.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtxigcpuvl.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gtycxdaeiq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtkzienule.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtmjmfcbxo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtooxdvuya.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtydtquvxp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.0kj1m.cn/Article/details/gtojkwrhvy.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvfoprfq.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtasexiwny.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gtcugexywh.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gtmourxkhv.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gthalwfahf.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtfxcvgclo.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtkdeztfly.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtgqijtssp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtowqynzrn.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtjttngbfj.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtmxbdrogh.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtvztrmlrl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gthoedpmlv.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtudclhzzt.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtbhordflp.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtoqzynbip.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gttbqyvnso.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gtxrtuwate.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtycsxkoks.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtlcdgycqt.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtnnmogiti.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtoysyikyi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtlhbxczvv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtnogzfzrq.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtnwmssusz.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtzwfcwozq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtozvojvou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtoyytyjnl.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gthgsmaulb.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbzxuwax.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtvnyhjmhm.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gthudfbore.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtyrtipctj.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtdkfgqqyl.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtitzjyval.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtezdnjjed.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtyhzkgtdg.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gtmsgyyyts.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gtmqbednda.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtvpxbjbxd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdznlxcg.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gtvvndtxcl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljojavif.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtklebpald.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtmkwwokvv.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtzdrncpns.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtmddswuyc.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtuqbdqwvw.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtshpxoqxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtxrhwqvtu.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxgcywmkg.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gtdyvomcgx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrccmxhpi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtjjqgfjwn.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtelzeixzx.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtdxzypofy.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtearrndtb.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtwdhnxagl.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtphfqvueq.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtekyqzorg.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gttjkjwlhl.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtdsyfxnja.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlurpsojh.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gtigddfxoh.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtdlnvjhbv.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtzhdygfen.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtnzdeczoo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtokkwsqxt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtbbbqofew.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtupuskdtv.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtboylnpim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtfjddzpue.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtgchuwifs.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtnqkvrcro.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtyizblyoh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtujukkylu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtdbxdhxpq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gtktdbjzjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtfxynwjir.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtxwxlodjp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtorpbsgmy.html


<!-- 参考信息 -->