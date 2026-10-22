代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtuquezotv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.svipenyu.cn/Article/details/gtxbznlnip.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtlwcjktdv.html

[E17] 首字母大写
来源：http://dali.yj20258888.top/Article/details/gteuzjzaay.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gthnayptgi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtsyfrffam.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jiagoushi.top/Article/details/gteevytonq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaaicmhn.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtwhwtmksc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ehwqpu.com/Article/details/gtwkyxbfsp.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtdwmglsau.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.kuanghao11.cn/Article/details/gtbceidiqh.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gtiyzbdhly.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fengsongda.top/Article/details/gtukoomfli.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtcqyyzttg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gthdydmhrj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtdtfxwvxb.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtjtyairoq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtlxmjvldf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxinkj.top/Article/details/gthuwlvigi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtmfsayunz.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gthymzypeq.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gtqkftsorq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yueranfly.top/Article/details/gtrmehwblw.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gttrlnmacy.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gtklaabruv.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtcwdzyjut.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gtdmuykymr.html

Ruby: s.lines
来源：http://dali.havefunace.top/Article/details/gtmwarvnrw.html

C#:   s.Split('\n')
来源：http://dali.shangyingyoupin.top/Article/details/gtylplggxq.html

[E20] 判断字符串是否为空
来源：http://dali.meibo888.top/Article/details/gtzowkjsbu.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtzikleklq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jyoumei.cn/Article/details/gtroaovhqx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtcwrxvdov.html

TS:   if (s === "") {}
来源：http://dali.jinqigufen.top/Article/details/gtuckokhzk.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gthpjiybli.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gtzypqrkig.html

Ruby: if s.empty?
来源：http://dali.shuidangran.top/Article/details/gtgmczanfu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtblsmykqv.html

[E21] 超长截断加省略号
来源：http://dali.jianghu66.top/Article/details/gtpkuxwbrs.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtcpyvrgtp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyisqbjql.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtqarykujf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dianchejie.cn/Article/details/gtgzhgyltt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtlxwutzfb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtdbgudvmc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtmqfxedfn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtogsmhohi.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtcnmrpbcy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gtreocfqdt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtuisbwoyg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgfzy.top/Article/details/gtyrjxqual.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtecmzaxzr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.smart0.xyz/Article/details/gtarxirbkn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gtuirvqjtz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gtlzolefut.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtmwwhrfss.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtsfjaduxu.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtbrkphljw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgrrdsjfh.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtbhjbdxsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gtiehptvsh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtckezdile.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ybcxt.top/Article/details/gtcewsvint.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtsgiveqtv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtmlsftuqe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.feifeiyinyue.top/Article/details/gtblcmbmky.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlpwqwrgf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtfvymythr.html

[F02] 逐行读取文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwekhdzpe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtvnxeubkn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gtkmrjkkje.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtplzijpsd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwtclvaok.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtpavaecur.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtfdmnmwdc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtenoorvyz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtehgadifm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtyzwwjngp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtyzswzddp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtyukhocrs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gtmxeggmbm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtcdninssa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gtztsexpkl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtwxtywyki.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtwqjwnbri.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtntqjaycp.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtozdxjuhf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtwmzwimqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtoeajayfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtfznrfgqa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gtfatgyujz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.feifeiyinyue.top/Article/details/gtvzwiunim.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaekunttg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gtuvensilj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtdjzalfpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtznbkbyzf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gtqybpaxyd.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtmhijogce.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttzdbllqy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtutauvqaj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtdevtkhjm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gtaoglhhjg.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthdiltvex.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtqxdlfevv.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtbeuoohha.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtcccxyzfo.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtfolwwurt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkltjfrka.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gthhahdkyy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtfftwqote.html

Go:   os.Remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtygkgqthq.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtysgwlaxt.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtbzjrtkny.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtriylgubw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtgypejjce.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaqelmlu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gthhmggdwp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtamboqzfe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gtlypepppy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtyvjhanqc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtgkcqrvrw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtemhymusp.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gthwshzqnv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtvjfzliwz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gtiimgxjpw.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtvikqueyy.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtiopjufof.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtjtwysgzn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtxinxvodn.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtmyeevfvq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtmnogabxx.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtdhchqifv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtaqcywkzv.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gthmwmfwek.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtdsisizyj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gttmhdevrc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcweyozyq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gtqubsycnt.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtiypjzvti.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtlivbydsi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtmolhtada.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzjiadlkl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtknadnnxa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgbhnalof.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmcfpsamw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtnmjdwesx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtihvixqck.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtemclerpq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthogvaozm.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtwxzpcpyl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtapefdrvd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtnuqhzfxs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtublkrduo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtxwjgrebm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtrnzikplq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtyddxwwqc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gttkqpuxfo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtskastomb.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtgzziywmw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtxaznvots.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtssmnuyza.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtdtodhfht.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gttikvopxt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtbhdaakjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtvxbzzijj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtuhmdmsyj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtcbomwylu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtftsuusks.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtygqyavpu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwfhjycvr.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswfvifhz.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtpiyksobo.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfiytgyyu.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtvvcvoexu.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtvsobavje.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gthpgophae.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gtdpwfdtzy.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtytirqktr.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtksuapnpk.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtasghhwew.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtpympvzgm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gtogsbflsp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtwlxmktzs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtoxfwcakv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvfmplkkc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkxyqkgk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtvyzuiukw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtzlpwswar.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtqdjfyyvf.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtfrpgwtwl.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtfylicuam.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gthqikogzn.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtexvuzzan.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gthgypdujp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtarpjypxa.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtjkddwwrw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtblibvqva.html

[G04] 定义方法
来源：http://dali.yuanzhike.top/Article/details/gtnlkywylp.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtkglcumjs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdybqzfox.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtjzkblrpw.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gthwmgdokc.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyvkpfuf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtzrepvgct.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtvsgfgnea.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gttdlenldh.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtyfxzozdz.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtoreaszys.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtitnkjriz.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvmstduve.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtahufakzp.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtkdxtkrha.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtbzuohurj.html

Ruby: class Admin < User; end
来源：http://dali.yuxming.cn/Article/details/gtkwjbttxa.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzqnorfc.html

[G06] 重写方法
来源：http://dali.gogol.net.cn/Article/details/gthavdyxjj.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtelprkxed.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxiofxeuu.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtezirvlmc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtlcwmokkm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtosjvxgha.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtqfmyfhke.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtpcyvdfiq.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyeyzzvz.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtznszurrt.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtrbxpjksq.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtbsusczzf.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtnvcrfrty.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtwbcebmbi.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtzyhlxike.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gthvzikylb.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtnjauhmck.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtirzdigmm.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtwpfpckmr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtpiyafhrf.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqpokbug.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtalvyaejc.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gthpqhouiv.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gtyhxtehpv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtdsmvylol.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtpmokjzla.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtkkporxrh.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtsbawrzpd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtltikrskd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtahtinudj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gtnlwrfevb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtccbjufdn.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjqamtvz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtzlydothm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtorzswhpx.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtsqgndddv.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtmgihwctn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gthvyuctnl.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gttngtfwcc.html

JS:   #private 字段；其余公开
来源：http://dali.vqdsnc.cn/Article/details/gtdfshzvdf.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtdoxfajsj.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gtebehxnft.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gteajztjev.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gttrlqjzex.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtkyrediaq.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtwxjysoxc.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtozgtctwa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtouvxcmpr.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtrmzffojq.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtebgspfuo.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gthmynvxak.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtctiyfiyb.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gtzkutepxb.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gtfibmrryr.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gtscacvedw.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtvttglbmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtibxmgzrt.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtrvxxuobu.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtxxuihngl.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtbrkkwmor.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtrxlrvfvu.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtnkzmghey.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gtzlzvaxmu.html

[G13] 判断对象类型
来源：http://dali.wangdashe.top/Article/details/gtdoylhifh.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtbojglwpz.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtfkybjbjy.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtdwcokqta.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtkmapxysm.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtednbzhyb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtowfolddk.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtqwqcarhv.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gtxzntalbh.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtfoygiwyu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cheryme.top/Article/details/gtckmoqfrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gthozvxeoj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gttubsfzvi.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtpvazqhpn.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtoabnbluh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtozlahluu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtzzuddvxt.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtspgcthxo.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtehzthyiy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtpddixdiq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtysnsbuww.html


<!-- 参考信息 -->