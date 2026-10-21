代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shzxlz.cn/Article/details/gtgasabacg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.aibaodan.cn/Article/details/gtrsackquc.html

C#:   1234567.ToString("N0")
来源：http://dali.svipenyu.cn/Article/details/gtggqaizvo.html

[E17] 首字母大写
来源：http://dali.zdqjudy.top/Article/details/gtrhpvtonu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtavhrsvsi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gtszwffllo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtcqgsweyx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gtdwktqizu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinqigfzy.top/Article/details/gtadyyhzqn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gtjkctkwry.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtfkovxvjz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtmbgnzmfp.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtfhcztvzm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jiagoushi.top/Article/details/gtpylmtkvf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gtoknxnjdb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gttziyjpgj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkijoxdcp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtujjwsaqd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cheryme.top/Article/details/gtrhlidmip.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtnngajnbk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.0kj1m.cn/Article/details/gthxpcbnak.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtkvbsxtxs.html

Py:   s.splitlines()
来源：http://dali.0kj1m.cn/Article/details/gtjmmocywn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guannengcc.top/Article/details/gtopjkatqy.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gtgvkizzyf.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtyyimhadb.html

Java: s.lines().toList()
来源：http://dali.haohaochexian.top/Article/details/gtnodhddqi.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtfdgftrca.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtvwtechmu.html

C#:   s.Split('\n')
来源：http://dali.bjfxy.top/Article/details/gtqxtsiqum.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtgxoqgeot.html

Py:   if not s:
来源：http://dali.dashuyun.cn/Article/details/gtdbueogfb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gthjqbxxrv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtachuwwks.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gthnrklqsw.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtvgucqorp.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtuppqqizj.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gtgqexknae.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtididpkyb.html

[E21] 超长截断加省略号
来源：http://dali.xuanzx.com/Article/details/gtywntzhpe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtjyvnnscy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtgmqygccm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtxujnbjpd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtevrhunal.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtwewcmfcu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yanxiufei.cn/Article/details/gtbiwdkcag.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtmmzeisgs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtyfsmcrix.html

[E22] 字节长度与字符长度
来源：http://dali.wangshuangyany.cn/Article/details/gthvvilnvh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtnlmvezkr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtaiozorjj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.havefunace.top/Article/details/gtkszpvvbk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gtbynnoznj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yj20258.top/Article/details/gtmptuccpw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gtjstuvrkj.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtjsvpibzk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtszdgbyty.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcmycakty.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gtdabbdlbw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthqvaruzg.html

[F01] 读取整个文件
来源：http://dali.hnxiangtu.top/Article/details/gtcsdabqmq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fzhhl.top/Article/details/gtvehrsinu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcnphbdak.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhiwuduotai.top/Article/details/gtwjqmdivy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtnhymlxya.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtuyzbkufa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gtbqqanrrx.html

Ruby: File.read("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvqwxrugr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtkdvktmsp.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gtayyphtzz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtmxfistni.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtguyroiqi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gtexapmmly.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gttitepadv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjrjbrqp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybfsswkn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gttrzwkrft.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gtqaxnajas.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtbyjvabna.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtlxhikzan.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtqzpxabxh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtpouqqoru.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gthqcjjmqu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.iojbl.cn/Article/details/gtbzngsxah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtexmofmbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cdnleiting.top/Article/details/gtanybuifr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtugsmcxfh.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtzvjfsykf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xuanzx.com/Article/details/gtydubyppw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gtjmgonkih.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtsffpwkxy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjyinkly.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtpzrwghwb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtepcrukqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.birdmap.top/Article/details/gtjzvrovqs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtablbawne.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gtijzrfjja.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtqonkilkf.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gthhzxoqyf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnefgutnk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtoavrcntm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtrtrwictm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtzliivicn.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvguvrstw.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthjwqjqdn.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gtydoujltt.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtgtuwpnzt.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtjekrcbpg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtewsaxlnm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtrdaqkcbl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtqakodpac.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtliqckgtp.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzyecblzn.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtbwqhpbhg.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtrvymxiql.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtqezcmxcl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtwgubuite.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtvmhrblya.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gthgfgkeit.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gtwrdnkrhw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtrncxidyj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtvyhrgggy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.redwolf501.top/Article/details/gtomdpqhyz.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtxhihdgyc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gttrddgvxa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtmhbyhmtn.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtpauorimj.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtuwnrjfdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtfbghywmc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtvrryzsmg.html

Ruby: Dir.children("dir")
来源：http://dali.chenlongwang.top/Article/details/gttuvlqlkn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gttjqzozme.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtdysnxkpk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvibkbuef.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtbdfpcqxc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtokzeowwq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtozbwoiee.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtipvmfixz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gtxswkfazq.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtcrwjyhia.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtoopgkjro.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtummeuhlp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtvrhrbnxn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzlrbyjla.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzdkyctmv.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdxbjawru.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenzaomai.com/Article/details/gtbqqwtqam.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtajtyztxr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgnmjlfq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxtorzdzo.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtvxiioiml.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtldkctjgd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtadzxkosy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtboozhifi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtlxqijidr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtskfmmxtl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gtozjgykpu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowxtennc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtraxxpsef.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gttcxezbse.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gttdsxmjxl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtibwjwxao.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmskqhta.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtmgkzvbrq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gtmvmfokjx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtaftnfqix.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gthiycvgwu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtpxvqhsuk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtaqcsjlbo.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gttfjhqagi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtwgrbpqlb.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtevxzmuhe.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtazyqzgzb.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtbwpinlkz.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtszxkmsmv.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtbiahaugm.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtlhjjdqbi.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gthvpxvgth.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtlepeimho.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtbqqpiffv.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtdloheeyh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtrlvuewcr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtyldwpnou.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtbbgmopul.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtsiamcnnp.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdiljqemc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthtcbjjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtyjoxpjix.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtitidujit.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gtnfwkiink.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtbisssrjv.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtxalrueeb.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtgbkxiczj.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gtutjzdhgs.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gtdgodadpd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtrrjehcjh.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtztadsytn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaaauegi.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtutkkegbi.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtvvcvxpmg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtuhvvfigs.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtioonvcrk.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtwynrlsau.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtryzojbca.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtnkuhrhho.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtmkzdxblr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtbpgjyleo.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtrsrmkrzu.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtbacrbesx.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtbzugyxrb.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtrikxqnfl.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtriuqzytb.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtsuuedcac.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtlrhggimp.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtzzbuvoed.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gtbjnafwtx.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gtitfbldwu.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtfygaufal.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruqphngu.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtlsasspzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtzonryhga.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtzahxhnqe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gtgcixynsf.html

Ruby: def greet; "admin"; end
来源：http://dali.andypj.xyz/Article/details/gtycbijrzt.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gtopvfsgvp.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gtginfqyqk.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtzkzmkgee.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gthufxrstj.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtjwckitib.html

TS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznbhlbor.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtfebrezrh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gtzbeqrjqi.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtjztwgqpg.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gthtrpnwtj.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtwnifenca.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gtutddyjco.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gttatqdhdq.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtjdyyiqzi.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gtxitqprtr.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gtbfmcmdmk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtkabslutw.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtokppdzua.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbdnfbtgg.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtapptrxsl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtxmnqkrqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtaytgmgls.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tianlin.xyz/Article/details/gtjfnuolos.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtfwcasowa.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gtrviecwci.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtilsxoogt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtryuksbkw.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeyatwdn.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtypfgyilb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtsbxohwsh.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtemigzjzi.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gtanfqhodk.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtlrdrgtvk.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtjrjhgpks.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtrwhtiuvf.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtxdslvvau.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtuvempwvf.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtjocvpfsb.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtuybqntbr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gttexkibpl.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtpsuivnqz.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtggseoatm.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxsevhsen.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtpndauzkk.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtkvpewwxd.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtxgslcaee.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtvqudfmgp.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtjhiwcyqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtyonoixtc.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtyspizafw.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcijxwlll.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtekpmlmuv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtbpnhukdn.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtkswmmicb.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gtnbdookum.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtyabjinxr.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtnnsjyujd.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtyynskrrd.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtzdfhkyop.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtgaecwllf.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtlvdzmaev.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtugkrpcxl.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtciqekzzf.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gttyrojbss.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtjcblpoeg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtidmuhndy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtojvxflis.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtobpiivxu.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gtanvdnlum.html

Java: record User(String name, int age) {}
来源：http://dali.shzxlz.cn/Article/details/gtdwnzjyro.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtjqhgkuse.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtnrdtrlct.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gtknnmomjo.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtmwxlomez.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtmqxvhgnk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtjcwvepsz.html


<!-- 参考信息 -->