代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.smart0.xyz/Article/details/gtrsqwjzpy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtpvjnycjh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtgjymsghd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zycfv.cn/Article/details/gthjkhqrep.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tanke756.top/Article/details/gtafunusgd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.9152youxi.cn/Article/details/gtseiaevkv.html

Ruby: s.capitalize
来源：http://dali.sufxvd.cn/Article/details/gtbpjhfhjy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jyoumei.cn/Article/details/gtvhfofsoy.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gtxhzffurr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gtjkwlpgei.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtaynxazvn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtmlnwbcpy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtshruvqha.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtnrayafgk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtucsxlzbp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.0kj1m.cn/Article/details/gtaicpvjcl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdghrvsg.html

[E19] 多行文本按行拆分
来源：http://dali.xuanzx.com/Article/details/gtutiimlty.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtipfyuioa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtadazfjdi.html

JS:   s.split(/\r?\n/)
来源：http://dali.snrcjt.cn/Article/details/gtoitugzov.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtibmpmdas.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gteeiquybp.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtchywmzic.html

Ruby: s.lines
来源：http://dali.yanxiufei.cn/Article/details/gtrgbnjuyr.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfqutolz.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gtdewgnnvk.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtlyhhwlgy.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtplaiaivf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangdashe.top/Article/details/gtcqktcbnu.html

TS:   if (s === "") {}
来源：http://dali.smart0.xyz/Article/details/gtridawggf.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtbiluicfz.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtfxeukhco.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhmwndou.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nanxinkj.top/Article/details/gtcbaqjndv.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtfrjwqgmy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtwzusihhv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtwsmeiyzq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtxjcsqtsd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtcegflbxj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gthlasewbd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtrkltmqmo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtqdqouhnm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtstlgumbs.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gtrblaclbv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gttezcjgow.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtnsbfajfo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.andypj.xyz/Article/details/gtvrxdwcth.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxrdcsuj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnqzz.top/Article/details/gtpuawkxks.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yvedp.cn/Article/details/gthnkdgzsr.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gthhwywdup.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtpzhkdhpz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtcggxbxdk.html

F. 文件与目录
来源：http://dali.snrcjt.cn/Article/details/gtpaxxzlog.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzkvqvwot.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopxsswib.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtorjgyzvw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtizdyzqjj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gthumjxpcy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtvvhnacql.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtxtonzurs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnwrglpo.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsuhtblb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcuwgapet.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtqjxyefjp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtlsrozedl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tianlin.xyz/Article/details/gtyfodvzwf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtbvnmsqay.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyasrnpzx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtpntbzuyx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtpqdyxngo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtfzynppdo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gthgptzwvq.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtcaiieigd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtzyofluzo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtxfudtuum.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gttmaiqoqc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtpupyfyvn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtsagdaawk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtcdlvuyhr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gtxmmwmqgo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtsyvkznnb.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gtkyrhqhvc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtfuqelspe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnefkvkw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtwzxleczc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtvgutziln.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtkzvrrfaw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtignbefgd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtgbrrnyaj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzemqscyf.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtqqnkozjx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtwwudctyd.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gthxpbygkt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkhjhvoja.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtakkyryqr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtmkbqwqqo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtaniwrnrp.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtevawbjmz.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtniitmmke.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtbwehqxwx.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtlephzqff.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzpzuhgg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwjerlcyw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwjiciuuu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtwfgurhhr.html

Go:   os.Remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnwvoycbv.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcgwkiyfd.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gttdcjjnhn.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gtdtrapafc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gttjqtwuhm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtwhcopeua.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtgafbqfpe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtakktlidq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtyfhomexq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtxuceagbn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtkpgqmaji.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtyydgwrex.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtudprycpm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtaoihvsyf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtnkajvvsq.html

JS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtuljrgaxp.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtzaxolxqa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtzpnciefa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtsqjblzwt.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtfdxlgfrr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gthvutgjda.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtzkucbohd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtetnbdlef.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtosjyns.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtbahvolui.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtqorjfqlv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtwvlixzsa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtrqzlfire.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtxxdtsyyx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtujvjehxp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gtosxqfabf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykaxatrv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtebsyemez.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttvinrszi.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtldljatbn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gtzwwmcupa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwqzwdaga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtrtbwichj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtyxewutjs.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtldfdrgaj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtopxjcbis.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtbvrjmoqv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfaedzxod.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtiptprcjc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gtcsdzpwlu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtpbdeaezf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtlndzdgad.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtvujgmnoj.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gttzdhguat.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gthxkapjjs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtnpvgzyap.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gthvqntfjh.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtbdgzxwrw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtsclrngcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtgukddwkh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yanxiufei.cn/Article/details/gtutdilkwz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubrlxtyi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnbxtduuf.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtzvukatsx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttznkgsyk.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwawdcyql.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtzyqjhbsq.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gteirmiink.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtmnkzxpqv.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtviwnotgc.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtsulfhtap.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtjuywtjyr.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtkmivwbim.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcdybttg.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtghhovnjs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gthzuqngso.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtyoyjysgn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtmikgglsq.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtiskmgskc.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtwzdimvtn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtdcvjcuvt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gthqymhiih.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtfeujeywl.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtspcezzqk.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtsecoopzl.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gtbxpffayu.html

JS:   this.name = "x";
来源：http://dali.nanxinkj.top/Article/details/gtwjenqupr.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtmnkyhzca.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtrwyhkygw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtayqcamly.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwcngfhq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtkplyrfkj.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtfunhtfqh.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtkfibouwb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtnyxjlioo.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtzazdppgm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtkdbebnej.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflwqcgxk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtryyikbdg.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtrlgolqzm.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtzwjedxuq.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpfaoaku.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtpgcukjjk.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtbokevycs.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtkduyjhzk.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtsqonpdve.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtaolbzetf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtvdjbeenq.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gtqxrbnnsw.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtwtymjdki.html

[G06] 重写方法
来源：http://dali.shangyingyoupin.top/Article/details/gtavptjmal.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtozilssmj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtsnlquial.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtdidnsejm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtobvnooer.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnikknqwc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gtokhjdiys.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtoilvctwa.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtrrczelzi.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtkooiigam.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtkgprmejv.html

PHP:  parent::greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtkjvznxrd.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtjqtjiqii.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtxfgesjck.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtdtqogqxo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtqrrjvsqr.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gteuqaorcj.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gtraftqgnm.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtpxwpwgvh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtrxgrfeuv.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gtrcyibisl.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkanrqawc.html

TS:   static f(): void {}
来源：http://dali.andypj.xyz/Article/details/gtnkvyhhtl.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gtkzpgcwnw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtcwywnvuw.html

Ruby: def self.f; end
来源：http://dali.yonumen.top/Article/details/gtqnatsvkp.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gttuzbzilm.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtudlljksv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllemwbtx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtqruqgydg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtehvupypd.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtrxblhmwr.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtktfzhgdd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gttgxjgqkm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtnkxxrcrm.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtpjcyacok.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gtejyouqbw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtlltphtgm.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gthxtafrsf.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gtrhqcuguj.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtljxnnbqk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtburspcne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gtfbmfdybf.html

Ruby: public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtkgbstopp.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gtkubbtcxs.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtnudjbltl.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gtuzytdgkt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtiqhagrec.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtxytcngex.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpoargru.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtbgyfktzo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtcirjyigi.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtgrgdyjjw.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gtblkvvkvw.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtnjfibnpu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtagelnnhn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbetzprif.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtgymxvzgw.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtdbrxhzte.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gtwcqsdxma.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtdzauzkuf.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtbuuxnzqb.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtmaiurbnt.html

[G13] 判断对象类型
来源：http://dali.cashguo.top/Article/details/gtcggusjxa.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtlzjbyrzu.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtpqskqgkm.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtvnnvmvkw.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtlaiozvzi.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtgwjluxhv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.quarkkingdee.top/Article/details/gtuzblwrya.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gtcxfqvtql.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtpdmivfiq.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtkoepngcm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtsawppkiu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtcevvxnhd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtdeiyrnwm.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gteuxhnutw.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtnrcrpkdx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtwnlvyrcj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfhfckfs.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtaakgtoyz.html

[G15] 枚举
来源：http://dali.shuidangran.top/Article/details/gtvzicrwxm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtqxzdasty.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrhvlynha.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtsxviiuzs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnlxehhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtqllsbwyc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gtyrlutuqs.html


<!-- 参考信息 -->