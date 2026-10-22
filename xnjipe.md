代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtnuzdttmr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xylfe.cn/Article/details/gtlamzglsy.html

C#:   1234567.ToString("N0")
来源：http://dali.chenjidiqi.icu/Article/details/gtbksjobcn.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtdzfwciqp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.guowangkeji.top/Article/details/gtfhjycvry.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtyxkswggu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtmssgrbpu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gtreduswnk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmghdhbad.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.nwbrower.top/Article/details/gthubxmfly.html

Ruby: s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtyrguhlgh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yongpay.top/Article/details/gtnxvuwtmw.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtdgrghmax.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtdtbdrzhw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jianghu66.top/Article/details/gtjuvebsut.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqsfnwcz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtjbejgemr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtrjxnedyl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtyjiwplkv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gtzypqcdxj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gttpcrylix.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gtkiopmerm.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gthsyhjmkr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtjhojtpbn.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtkequbkub.html

TS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gttkotqncx.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gthbocoopi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhixingplan.top/Article/details/gtovdkleqq.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtcgptlvlb.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilzorbfn.html

[E20] 判断字符串是否为空
来源：http://dali.xinyue.icu/Article/details/gtlddygsex.html

Py:   if not s:
来源：http://dali.gogol.net.cn/Article/details/gtzinzhrox.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhixingplan.top/Article/details/gtqednvvfw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zycfv.cn/Article/details/gtezsgvopn.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gthorpadko.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtkmhyezug.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gthvqzvuqh.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gtceyjnnuj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmatcuaxw.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtqqloyrjt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.aibaodan.cn/Article/details/gtpfopduro.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtdljxniui.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtsgotholh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtljpkfzus.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtzmratbux.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtdkrjylgd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtxumqpzwo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtqylghhaz.html

[E22] 字节长度与字符长度
来源：http://dali.hfpthk.cn/Article/details/gtvfauklwp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqftcslgp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtrzmuijrz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtkjcfznpa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtdnibznyu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xylfe.cn/Article/details/gttzfpifkn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtpmgvjvtb.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtissxnami.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtuotjlmpc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtolioukdv.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gtugbsntoh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfdypqwpb.html

[F01] 读取整个文件
来源：http://dali.sxryk.cn/Article/details/gttigzswbw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhengqikj.top/Article/details/gtfczixrcd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnmbvqer.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtgzllqesn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtskprulcq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtpeikbpqy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtkpdiqxtc.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtsgyqukcs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtblzudzak.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gtdwmepaue.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gtypqjhptj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtdfauyful.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtibifwavm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtdqbwsgcb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtnwxtpttf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pengpengdd.cyou/Article/details/gtejtjvzlr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtfvyuvnvo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtkovxowqf.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgufenzy.top/Article/details/gtidcibyas.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tanke756.top/Article/details/gtnimeglup.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtjqoelulk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtbfxmkvpq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtiblqoftg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtybeixarl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gaohongyu789.top/Article/details/gtyyqqtjae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtlifqiwls.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtjsmnxzte.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtwjieqhyj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrkkoirk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtzhflyjdu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtpklfnvip.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjzzkeiy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtxkojmjnc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.smart0.xyz/Article/details/gtslaghwft.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtaxuelmbc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtdxiqdoje.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gtkkekkbvw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlemdrzlq.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gteacripol.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtboedzadl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtlquemkic.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtctndcggz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtxleggxvn.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtnknpsaez.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpwakexmh.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gtgbltcfob.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gtlntgeqeq.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gthlhbdncb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtggmdddsp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtczwjnwao.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtbtaesmst.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtkznrgzrh.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtioyadkrj.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtithfvuee.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtwerjlupi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtuortfytj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gtubhzjabi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtjtogkccy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gthbxoozzy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoivyuatj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtsbyloblf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yangfankeji.com/Article/details/gtrpslunrs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtsexlavnq.html

[F08] 遍历目录
来源：http://dali.snrcjt.cn/Article/details/gtsjfwvrlr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtrwsitlqa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtiknfqsml.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtqgskpusm.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtnnvfbmln.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtehmuryvj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtamviqziv.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gtbxvkkfau.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtmyrbeouh.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtdezuulkg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxrhcwqoy.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtmkvgdqfj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtdpvoulxz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtdkbqyedt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtxpnarkpz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtdrxumsii.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gthpawuxri.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtewgwpthu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yangfankeji.com/Article/details/gtfhasygno.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtwqapobku.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtcrcjquzz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtviwchdni.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdgotkqap.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwngtxaya.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gttkditqzq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtprjjceyo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtotlimrlo.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtdkrqitpc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtcxnevuid.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtxxpskrxa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkkarjgcw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjwfmcusz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtipjvyiwh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtrewarbbj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrmpohlwi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtlurfrxsh.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gtvntupamv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gthklwltln.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtwbqliapj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtwaevvaog.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtvheovuyh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gtzxxbcsde.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtxykvoiho.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtgpzeevhv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtkfighvro.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtueznjnzv.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtgcmaboit.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyqhhhwvw.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gtucfceexg.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtiibdbkbs.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnunnkogr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtlixhukxm.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtfxyswgyy.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtbiujwmbn.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gtfcqaexhy.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtcznbcjrj.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtismhpwpc.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtibhhxlxh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gtctuozesn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtwnboduhy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtcfkphnqr.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqntmkyqn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesfvyvnd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtrvpfxjoy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtqgbiqfrt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtivkwtsbi.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtnfkqdqxi.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtjscpquwg.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtypmmncck.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtqatddavc.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gtwmfrsdxz.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gtzehncfcu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtjmptijtk.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtzxdbhaup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtglbhmtim.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gttpsngkul.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtecihlyce.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtcxieumtb.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtcixrgpda.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtqwjvyvgk.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtgafmrovv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteufrsltj.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtgbkbkmrk.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtpiynagmo.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtlomcispw.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtgqcmlyjg.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtyajkypdf.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gthnshqsvg.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtghmgohmd.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtfvgieaqw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtkpooovpf.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtnnjerqmf.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtcbybsnst.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gttmnrsvsf.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gtsgxmvurq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtiirbyjev.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtpgajcmsc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtufimdogd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtbdwlenmr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gtcavahobq.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtgvzzodlg.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gtkdmpzgoh.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtdaxuatdp.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtaxbvqwoe.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtmxaralzi.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtbpkzxkow.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtjvhyfvju.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtamuwivli.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtesxqfyib.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtnjseconm.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtijueelkf.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtehbgoboy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtsgnkbgvg.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gtxkkncjvg.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtzovfwzgn.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtzwqpswnx.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtqvhxmlzw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtyvycoxnl.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtatlccslh.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtpjgqfylc.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtkvuemkpm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtpetypfbu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtpthppmgi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtywbivatr.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gthdknlfvs.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtlkxfyjoq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gtdukjkpcx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gttyiaroxu.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtmktngsns.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtxrcfzkzz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtondspeou.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gtltcnrmfj.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtguffbqrz.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtuybfpyew.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtsegewybb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtciiptovt.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gtvvjtaixw.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gthdtmloac.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtxdychtqo.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtqvvdlerk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtmdyjgpkr.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrhgkdhg.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtrmtsodpv.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcgobcstt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtnokixqob.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtaqxwgruc.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtgdnsoshb.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtoxwtbozf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtrdqvljem.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpzbrczqu.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtkqscawvh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtibcibfsz.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtzhwiiipj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gteidxcylr.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gthoicufht.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtkqtivros.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtugdwugtj.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtywrdflox.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtaucbvrjw.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtdjoanfcg.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtlecnknpb.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtbymucdev.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtbslpeohs.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gttianaekb.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gthrwzdnxm.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsexepyf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtralqgdtx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtlnucsmhc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtgxmltwfy.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtsbwyxhzj.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gtyzbllqsw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtwookimnf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gthobltaoz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gtezlklyxa.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtkukppulq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.quarkkingdee.top/Article/details/gtfnmlkpuf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxibombtc.html


<!-- 参考信息 -->