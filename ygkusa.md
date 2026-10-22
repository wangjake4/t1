代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.c1oappe.top/Article/details/gtpgpunfwl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xziqi.cn/Article/details/gtiqdpryma.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtnrchlalz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gtqidbyeho.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gtrbtwtokf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gtqpkkqbqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gtjnsvilop.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtmsudqtda.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gttnnopydu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtrnnqohot.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtoobuplft.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtoptdlhxa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhongyouzk.top/Article/details/gtvwwwlsok.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gtkmxfkrhr.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtastatudr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtbcopgslj.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtkywqazqd.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gtmhxcemot.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtmmlllstc.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtkwhdwwsg.html

Ruby: s.lines
来源：http://dali.nanxuanxn.top/Article/details/gtwaivpwsk.html

C#:   s.Split('\n')
来源：http://dali.ybcxt.top/Article/details/gtdywhqsbf.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gtruygufxt.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtpdvtouhg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gthuuzypay.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgfzy.top/Article/details/gtdmhiajgz.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gtpvvzvcia.html

Java: if (s.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmfmdjbdv.html

Go:   if s == "" {}
来源：http://dali.zhixingplan.top/Article/details/gtvucgszlz.html

Ruby: if s.empty?
来源：http://dali.gotoacloud.top/Article/details/gtnrycbuzz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xylfe.cn/Article/details/gtrdkvkhqt.html

[E21] 超长截断加省略号
来源：http://dali.hnqzz.top/Article/details/gtofgkkvar.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jiagoushi.top/Article/details/gtclmtplal.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtvfodnhbo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtsksrmeqo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtlgqyezdz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtaooaagnl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtuirdjozw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtgmzbnvgw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ivvv.top/Article/details/gtohbdqdlq.html

[E22] 字节长度与字符长度
来源：http://dali.nwbrower.top/Article/details/gtdirvrvis.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtkxxxkzdj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtmjwjfdvm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gtvocbhtrc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtyvubuvqg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtgdbwpdhf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtbdncpppq.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gtmmnwrnbf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtuwxejfpg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxijhxrgr.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtpbbejyud.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtvhbeyxku.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtzqaktqyx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtztnyxiww.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtvcibztps.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gtffclmaaa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtydqwdwcg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtqlsivddx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtqohqxmta.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtryxhqqxb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtbznlzfiw.html

[F02] 逐行读取文件
来源：http://dali.jqgufenzy.top/Article/details/gtqawlrtie.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtmsypxqwx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhengqikj.top/Article/details/gtwkbswbqs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtrmxuezlf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtqtwzssbi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtcvkhohos.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtjlnkmicj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nanxinkj.top/Article/details/gtbdzurfdg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtcarezhtf.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtzqmzjatn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gtlhhhjhae.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtodpfwcdo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtghddvrug.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtpjajocfl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtgdrjhopu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtqjlobxif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.haohaochexian.top/Article/details/gtbrwopvqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gthoksgqkl.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtiwtwipjf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtayfzmlmf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtkvljinba.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtbxehrasn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtlgrrzzff.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtvbqfxbwe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtpverszoz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtnianugyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtoirksego.html

[F05] 判断文件或目录是否存在
来源：http://dali.nwbrower.top/Article/details/gtzbtsnsjq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtemezqtyz.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtqzczuniv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtqxvojhje.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gthfzhmcmq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqrwteez.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtytxatgaf.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikfepgzr.html

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtfycvmtll.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gthxevxyed.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttomuekds.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlazsvrve.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtxljzcdgm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpfpmpmpr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtlmtijptw.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzihprrnf.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtquxdusck.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtlkrrambw.html

[F07] 创建目录（含多级）
来源：http://dali.zhengqikj.top/Article/details/gtkxagiabm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtlidrrvjy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtvbsmieli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gttschivfk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtkesgsrdr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ehwqpu.com/Article/details/gtyiodxwat.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtfjmpveja.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtlzjlprox.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.svipenyu.cn/Article/details/gtoqftccah.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtwgsciusp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtzllmlhoh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtyqdebgxj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtogmarywj.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gtwdcakaig.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtsncxmdln.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtxsilizhh.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtoewhmkwf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gtjjnlbzec.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtrftxczme.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtwupddwsd.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtyyvyumwr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gteapwzaow.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtysmgnruh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtdboxhkwe.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtmtepsymo.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwasbkezw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtwrryxvdm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtkavxqydp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtpnpojixr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gthlxkdyuy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzyqoakaa.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtwkzzdlke.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtqfrgtdds.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvdqseigh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtucleajtu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtbuedvuun.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtsyhbuhys.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtpwwgppwy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtaifatjoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdnfcpkm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtzogdzvek.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtcecebxzk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gtjyyjmlup.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtpexaoqlx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenjidiqi.icu/Article/details/gtcdlkqukz.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtdolomrjm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgfzy.top/Article/details/gtqrbmlsut.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtfamcrhvo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtimzvvcal.html

TS:   // 同上
来源：http://dali.daria6918.cn/Article/details/gtxvvnzxha.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtbkxqrzos.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtfnnmgbbn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkccrwplc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gttvtgwdct.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtuysfufba.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtsasldaai.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrbbfthhv.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphhfdufs.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtdtjeoork.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkyapvqzo.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtrlpxhxig.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtekqiricn.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcptjjeyx.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtgnyuiypj.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtnqtsdwqw.html

C#:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtactvxvqt.html

[G02] 构造函数
来源：http://dali.9152youxi.cn/Article/details/gtymigcpbo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtixyxcron.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzchnevjk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtktxkefvg.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtnyuifbwh.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtrsnkxhjv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtbltdzcow.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtcttkjypo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.316326.xyz/Article/details/gtpkeyfsyg.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtjrddnjaj.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtqtmyflak.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtgcdipygp.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtzcwicdfx.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtcpvswiml.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gtgypbyixh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtdulytdbm.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtzlbssdvo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtwtsqescg.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtzmzxdddl.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtlilqqxas.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtrpdsshwo.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtnrggfsbe.html

TS:   greet(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtzzdxjgft.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtrifqdjiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtvhghakbp.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtwhrgxrxv.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtbhkntaqj.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtabyqmomu.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtpgukgcjd.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtivoyddjz.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtxcndalzl.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaizuzgt.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtyevestep.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtbvrbrxtf.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtmmpevgzn.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gtzhjnkyfd.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtsvzzperq.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gturfeqeky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtefpduxkh.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwaffkbgm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtxdcdsimm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtyaniyigj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gthvakjefe.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtlevciedn.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqihsjsjs.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtjrfvgezq.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtdqfockhv.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtgnwmsuij.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtbzqjgdol.html

TS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtynkpehea.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtxglqmtfm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtrxxzlwvo.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtcozcsqab.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gtcuoqassk.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtghjqezhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtshormyco.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtinosxaoo.html

JS:   static f() {}
来源：http://dali.cheryme.top/Article/details/gtfbgrqpqj.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gtzngsppuv.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gtjqkggssd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtgwbwubtz.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gttmbzdyfm.html

C#:   public static void F() {}
来源：http://dali.nwbrower.top/Article/details/gtdezafjos.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtykvseqsd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gtgnlhrbjw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtgsodandn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.9152youxi.cn/Article/details/gtxtxioawz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtifnnrjme.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gthispxkeo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.feifeiyinyue.top/Article/details/gtvvfbvfxj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtsjnjlgxp.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgniuoqtx.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gtvuzxeolg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtombowppn.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtjfqruuod.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtlrclcmje.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtrskewwom.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtaqzvrsef.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtmorotdzo.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gthlrukqke.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtegevlrfp.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gtvfciowis.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtdcvkluwh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gttubpgrkn.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtwuvuhreq.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoinrzeur.html

Java: public String getName() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtijgziysx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtuhpketpu.html

Ruby: attr_accessor :name
来源：http://dali.gotoacloud.top/Article/details/gtkrenedfm.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtccqtjxjj.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtmjegqqpo.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtxrebpmye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtsnqawjbe.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtjgqqivoi.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtasmzoemx.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfozgggum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtcjbgrzjy.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtocjjrqxv.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtixgjcdxn.html

[G13] 判断对象类型
来源：http://dali.yj202588.top/Article/details/gtpnwrnhvp.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gtfebhhyva.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtflqthqbe.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gthhycbees.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtbowvwosx.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtyzmadsro.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gtdowfgouh.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtrjdhncar.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtgnaojknr.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtedaeerbj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtljszpctx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gtopmsokca.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtdnxqacdw.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtagphcrbw.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtnkvluanu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnjjcsws.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtnscppdki.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtiphgzmdf.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gthueccrwj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gtkbbuckqc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtxfddmiqo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gtrdvddapb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtnxpcyxbx.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gtsawublqo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtgpzsqoch.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtckoknwmf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyhxachx.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gteopdrtvk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtrmnfltdk.html


<!-- 参考信息 -->