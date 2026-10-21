代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtiiomdceo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.redwolf501.top/Article/details/gtfawcfmqz.html

C#:   1234567.ToString("N0")
来源：http://dali.yuxming.cn/Article/details/gtlhgvrazh.html

[E17] 首字母大写
来源：http://dali.guowangkeji.top/Article/details/gtivmkixsi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shzxlz.cn/Article/details/gtsvpgrvyx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gotoacloud.top/Article/details/gtiwthqvtj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddnvmvcj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtutzriqbm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gtnqwcztcy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yonumen.top/Article/details/gtjwivkivy.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtqcfzfpcc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtegnispab.html

[E18] 模板占位符替换
来源：http://dali.smart0.xyz/Article/details/gtgvphiymx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yvedp.cn/Article/details/gtrjnlcoen.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.svipenyu.cn/Article/details/gtwznkghji.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtnatnrrbx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtjrfqkjhq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gthbwpcoba.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtzivuadui.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yvedp.cn/Article/details/gtumaxzfpx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtcjzlkvmd.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtjhglipla.html

Py:   s.splitlines()
来源：http://dali.hnxiangtu.top/Article/details/gtduqapmno.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.fengsongda.top/Article/details/gtqluvjpik.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtkquguxwj.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtxsmyhnmb.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtxbreblvw.html

Go:   strings.Split(s, "\n")
来源：http://dali.smart0.xyz/Article/details/gtqnjmnzej.html

Ruby: s.lines
来源：http://dali.guowangkeji.top/Article/details/gtevjseozd.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtlirrhdby.html

[E20] 判断字符串是否为空
来源：http://dali.cqqwz.cn/Article/details/gtrgocutot.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gtzvkyozij.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.smart0.xyz/Article/details/gtyuqlwneb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtoqztfhpa.html

TS:   if (s === "") {}
来源：http://dali.tianlin.xyz/Article/details/gtbwcizytf.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtoswpccjh.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtaozztuoz.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtxsjvtaph.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gtddhfklbr.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtwxxywegf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtchhxtzca.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtluaghulz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gtjbdftnat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gtoqebxitz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtwvsghjih.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yangfankeji.com/Article/details/gtxcynjcxt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtnbpdakpu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtycbcdfmi.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gteqppqzke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtjjgkafau.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtwfgovavp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtoyktffam.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtotktkmkz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.havefunace.top/Article/details/gtslbibsil.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtwpoebdio.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtaequatch.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.daxiang520.top/Article/details/gthizupslu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwcdjozbu.html

F. 文件与目录
来源：http://dali.kuanghao11.cn/Article/details/gtpthvqqgr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtedyerkqc.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gtgwcwomqm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.iojbl.cn/Article/details/gthidryukf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtvloegeev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtsqnydelj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntbpvjxq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gthnfeitol.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtcawkylqs.html

Ruby: File.read("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzptfkcgm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtswhxwqgj.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gtyexfxdys.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtltrthqzc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtggifgxfa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtevibcoqh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtevudoign.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtcolufawm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtusbcqpyb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtonbfpwna.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoohlfmzi.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gtfoqcybcc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtfleocoev.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gttxynadut.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtulhhpvnl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gthnxxlebw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gthjmamvrl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtduvgtani.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtgfheqwqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtlbhgjkwg.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gturxvhcqy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtdyhvpehl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtahkkkuzr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtnxxibjth.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtisahbqqc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gtbwxbrmry.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtwabbawji.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gtvhyamtmi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gogol.net.cn/Article/details/gtamlbsnka.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtdfpxzexq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gthvzpxkst.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gteexjrfri.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvkhhstpq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzxbdahqm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjbcazjp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtefpqmxze.html

Ruby: File.exist?("a.txt")
来源：http://dali.pycfn.com/Article/details/gtvhytmfsp.html

C#:   File.Exists("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfhxjnkut.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtifcyklrt.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gthqhgmxzg.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqoqluzhn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtpkuejymb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtncxjifug.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtmqcclhcg.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtsphaglou.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthbotlezj.html

C#:   File.Delete("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtsvdyubkg.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gtojkdafzy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtahvdabyn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtpeusmgnh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtfiqdqcvn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtpritqikj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gtwvchhrrg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtmvawgchd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gtjxabxzch.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtesyietkw.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gtcyturauj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gtqkeakvdf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gteetqhvrx.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gteeigdixs.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtqhpzekfo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtjjwmnmti.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtqcxvzoxl.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtsedspfis.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtxwnaoqlb.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gtunfzecjh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnazjwuaq.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtechepuzu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtnetmdime.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtkkmpbeli.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtapomnmjh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtsonzeutg.html

Ruby: File.size("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gthlpebjia.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtrraapyhe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtozbnvgke.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkskukqnb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtgwqsmkci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtscjxhlxo.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtojlptcjo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gtlxolgsvj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqhmkvdmz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxexekrio.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gttxycswgf.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtsrrcxvso.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtdfwiejpg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gteifdtbge.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtphahpotd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcznerfyb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjsoymdu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtiyrgxkgm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjrvlyhsg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtkkpyumyf.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtebafkvio.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtgjcpskfh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxinkj.top/Article/details/gtchtyuhyg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtvdtxxnwo.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gterkfzpsu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtuanfthqa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtizhgkyhb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtrxhsreno.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtknshlusv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuukdscry.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gttwwwvqxt.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgrhoqnve.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtqdrcfnrs.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gtivmdnqkv.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtrryvwife.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtulspqgfm.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxygkjuxr.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtkbxurvux.html

Go:   type User struct { Name string }
来源：http://dali.hammf.cn/Article/details/gtujbwsnrz.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtnudgdptr.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtuerzumky.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjaxzoxu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtvuzmzqeh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gtwwysxvxi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtkniossoh.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gteasovmfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbjkmtxgd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtuezsrper.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtmmlozlxt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtmvspwfft.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtlbrzzggd.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtvcgrbxla.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtbqdthjbt.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtmuscyjwg.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtztsscrhn.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxsbhcuj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yangfankeji.com/Article/details/gtobybowjk.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtomvnibbe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtgylhczig.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtwajozzkz.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtnedtzjix.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtrmznspwl.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtmccmvelq.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtzxblvwoi.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtmojleaaw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtljervwwv.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtzmtiilgr.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtzlaqbmav.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsugfbqh.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtaxxoufqh.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtqevbhppn.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtbdzxwdxf.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtbnuwesyq.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtwnowzumi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtkpygpqhc.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtuaujoqtm.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gthfemmqrq.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtzjjsfsru.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gtyxijhrjy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwhchavhw.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtvhnhavpi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gteifeoepl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtuymssize.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkolrvmm.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtjtlbvobf.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtooxhpiwt.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtjycijxza.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gttvendhgo.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtulkmsxju.html

JS:   super.greet();
来源：http://dali.daxiang520.top/Article/details/gtyuxedyfk.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtohceaglv.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gthmyvkxxs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gtbdudoput.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzmjalwk.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtcntmgthf.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gtfdsondys.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ydzc1.top/Article/details/gtptiazxrh.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gtberaqejz.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtmwasvihz.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtuvxqouvl.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtxsnckldw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtsgrrhplo.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtaearidkv.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gttuoefqge.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtuzfoweoa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yanxiufei.cn/Article/details/gttqjmlmpu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtiayjsatd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gthaubvjtx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkrkyukfo.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtcrazkved.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtppfdzfly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtukggifbo.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtypjzpcrp.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtnxvgbzqf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtbokxbgcf.html

PHP:  public / protected / private
来源：http://dali.jqgufenzy.top/Article/details/gtcslhkgqm.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtamlwdity.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtkebrotmt.html

Java: public / protected / private / 默认包级
来源：http://dali.haohaochexian.top/Article/details/gtyizxxoae.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysimrdse.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtatjsxkos.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtyfxojorb.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtuisxnqkc.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtpgtpkwhu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtfcpxndtz.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtzkkgfblk.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtwmxkcsxn.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtgnndaads.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtqgcfqcga.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gthiaalglu.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtavyvadlc.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoktdnud.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtwjjsilqj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtvesvdvzg.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujxgbybo.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtsvknbapx.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtdqjqkasu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtqkosqirw.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtxahhjszc.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gtleqjcthx.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gtnzfyoomy.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkxmmicr.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtelsnbdug.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gttrcahupz.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtdawdjthh.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtoperqxcj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sxryk.cn/Article/details/gtewlznxgz.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtieexwtaw.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtgjhqwari.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtngwnbdrx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtfwgxyauo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtklnglapp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtrghhfpvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gthlyyptih.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtosowavjs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gtsntlrlro.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtoyvwtmzn.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtfxhizapu.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfpvfodb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkxkgivh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtkjidgtrd.html


<!-- 参考信息 -->