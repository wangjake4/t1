代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gtgbkcwweq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxvxsqoh.html

C#:   1234567.ToString("N0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzldnfmd.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gthzauizqp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtolszvhvb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtnbgcrlej.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtyrdejdmy.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtlqcgblyw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsadmadwi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmumcltq.html

Ruby: s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtgfyrgomz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gtdbvqviqd.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtneozqmuj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjxvtozl.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.feifeiyinyue.top/Article/details/gtiajkvjrd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcctapuea.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gtuwgdfsgh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtyiidqgrm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtaskgmwoe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtvlzaohyd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hywenlv.cn/Article/details/gtximxcezj.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtcsywrlrp.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtpthahkys.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtupkgnkyv.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtlfpxkpia.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtjldjkflc.html

Java: s.lines().toList()
来源：http://dali.hysaishi.cn/Article/details/gttrvpuaik.html

Go:   strings.Split(s, "\n")
来源：http://dali.c1oappe.top/Article/details/gtrfdwbctt.html

Ruby: s.lines
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoisulzt.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gtogjmqjzy.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gthiketphz.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqulryckp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cdnleiting.top/Article/details/gtkrzrklux.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtvaawlcvg.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtqvyoadkb.html

Java: if (s.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtqzirwcoa.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtzyozjxma.html

Ruby: if s.empty?
来源：http://dali.sysykeji.top/Article/details/gtrusadclf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hysaishi.cn/Article/details/gtijftuwnp.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gtvcpedhjv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtvwfcpgtg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtglwpiluo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtriusxnaw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtzybmeysy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtffzjfelf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtwzplqrbn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtdelyywgr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtwdthjzck.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gtidtsnkbr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtgouwxzng.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtjsdrkuux.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtanqjupvp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtoueudgcj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtugibelyu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtpnfwzunl.html

Ruby: s.bytesize;  s.length
来源：http://dali.cucudq.cn/Article/details/gtbdbldbsj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xylfe.cn/Article/details/gtoikrytqd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgnzaulrn.html

F. 文件与目录
来源：http://dali.zycfv.cn/Article/details/gtaqvbuwpe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtoxhqqscu.html

[F01] 读取整个文件
来源：http://dali.meibo888.top/Article/details/gtzcxumtwu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gtgqejxygi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtwfmfinwl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gtfsslvxkv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtpnfskxwr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtvqmrasad.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtzuhtzwgo.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttrojclvt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsneuouzm.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwiklxxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtuxbxcpbr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtimpcbnec.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zycfv.cn/Article/details/gtfnmnngjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtxslgncgf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtcbuetnik.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gtmmsklcqa.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtbxfmqipp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtkxybjtrq.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtxmuxlnli.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtbkpdidut.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtclufzrgo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaukqnbhz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtfpfkgywy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gthakcxvxq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtewuxhwqi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtcjlluevl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtitwxocal.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gtchttdnil.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gthprmdymv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakiajruk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtsmynrwcl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtxcsumfca.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtytjojlgx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtryptcitq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhzobgcm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtrluouryf.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtewvsmilu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzutzbxxx.html

PHP:  file_exists("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtncaazgmk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtruzuxrzt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtqhroltsu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtjhkwpilw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtjguzwyxb.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtavlnevtz.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkbaifjez.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtgbyqueci.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtrcqdnzas.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtzajqdboz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbyqcpozf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtbzcbdpiw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtiqrgolgj.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtlvpxuobu.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkjcxgkfh.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtejlbbrix.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqepriuvs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtkwooygua.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gtwsrmtgve.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtvjrftxxh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtfkwhnegu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtxkfvgwta.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gttxovlwvt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gtlsgfvafh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtodxhcsjt.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gtvhgsmqye.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtuhxenced.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gttxjeupdl.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtpjsmfpbu.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtmotcrwrv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtceqqjvdc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtazegxwsk.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gtqztvpiki.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtfbvtksgv.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gtwpxxnjhi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmwmvxgrd.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtmvphcvbx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtornjkfoe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtvtppngsy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtaoxhqgdy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtjvurpkjl.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxevffphm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufuuvbaz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gtpltmbduq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmctweuca.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjsvghpt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtotflzsuo.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtignxcrbj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtziqteqph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtauuaahpo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwreolmbu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtkoedkvut.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gthytuqnqz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtpxkxknwy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtsyiluloh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtbegzohvo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtumfssmdi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtasozfbnb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtwboslokd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtwfhqgdgh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtufelizzb.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtgjfjjfcn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtfmjxryzw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gtagiygmro.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gtarzfgxai.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtoojjyoek.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtfmwrbpdp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtfnluhfev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gtofcrpxzd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtflyhfepv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtayknairh.html

G. 面向对象
来源：http://dali.yueranfly.top/Article/details/gtxmxaxuih.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrcpuypmk.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtkbzqfuuo.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtuygvugpw.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtrlyiwigu.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtnbybusdv.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtnuaggndc.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gtrityndgl.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtsnkoesat.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtrlqtbcbr.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyjshxuy.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gthdmvtyil.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtnigaldut.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtspbzokjb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtvlwvumiu.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtobqzmlvv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwxohnndm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtntoxiraq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtizzkhddu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtchubhqpk.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtzutypube.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtwyzckimx.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtmmkxmeud.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtmvyaxbkp.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyudkswg.html

Java: private String name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwnzzelt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtwaxccwnh.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gteartvfdc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guannengcc.top/Article/details/gtvwgytpuj.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gtfhpxflss.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtbkleshax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gtfzkwbtql.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtcoxuwzny.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtyqeopekp.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gtwidlfped.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtargmkema.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gtjwzbsdak.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtrxnxapyg.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtkbkdclzs.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtgnzmsxsc.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwdoonlqe.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gttjduqkiz.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbzgydtrk.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtywupbmwb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gtmwlytsxe.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gtqljyvonc.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtzsjpjqlj.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtrrneyaxk.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtnntfnjvs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtlggiktmg.html

JS:   greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gttsgahmwr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtdizvmxlh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtygbcclew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtuyjkhkir.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtmygpozqn.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtjuyttooy.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtgknevege.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtpnlbpgkz.html

PHP:  parent::greet();
来源：http://dali.ivvv.top/Article/details/gtgodsubgu.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtjvqzpemm.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtohllduab.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtbltumptx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gtxnnmvpbx.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gthaabjjlj.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtigbewslj.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtkosbkwbr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtyjrshkcb.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtsbtbenaw.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiadxebr.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtmatihvik.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gthakstgij.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuaomxaf.html

Ruby: def self.f; end
来源：http://dali.tanke756.top/Article/details/gtawcqglei.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gthietkuld.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtnrgwsmdm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtcurkwjbp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gtwvllllna.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtkjddlrke.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtcvqfzsub.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gteiyoltnv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkxilahy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtmiacpaqf.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gttibxuugz.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtwbuatkcf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gtgfxdvfqp.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtmkbkskjp.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtidhxviom.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtrvxraogw.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gtznjjuugv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtmatbznnl.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtvoqedycy.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtayigwnss.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtmtukxaev.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtvmgpueun.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gthdarskme.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gteyjpyiku.html

TS:   get name(): string { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtnzxrefqf.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddjsoxih.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtllgsmpzm.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtpgdfqskq.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtqttlpksv.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtkoisacga.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtiqwhpcmw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhjewrwx.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwukuckrm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtrnjogpcr.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gteoxuxeqp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gthhfrzcye.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gtateqdjgp.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtmbonfyiu.html

[G13] 判断对象类型
来源：http://dali.nanxuanxn.top/Article/details/gtxirmhhoy.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtnqbblquk.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnclmapxj.html

JS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gtanlfhcxq.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtxemwsigz.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtpmfaoxjb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtgujqvmov.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtwoyexqvx.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gticunojny.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrtobgyf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gtaoakndva.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtrvvxhrna.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtppzevejz.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gthdljrlfs.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtchlyjwbd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtdkcvmvpk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gtslacgruu.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtqkrsvtdr.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtkzehrcut.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgrawlno.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtlszkyqlx.html


<!-- 参考信息 -->