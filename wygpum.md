代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gotoacloud.top/Article/details/gtnuqbdaaj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtwqbcwtqd.html

Ruby: s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtlsljlcee.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gtyiujmiaj.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gtobpgwqcy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtxdyrzrdp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtatchsnht.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtcubxqobr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtjophayja.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpgyyboh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtqqavvmuz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtoqochhqv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gtjdccieeo.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtvomvysns.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtwhwsevwp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtvaczlzjn.html

JS:   s.split(/\r?\n/)
来源：http://dali.ppjwa.cn/Article/details/gtsrykrxzg.html

TS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtejgwqogc.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gthxelejev.html

Go:   strings.Split(s, "\n")
来源：http://dali.ehwqpu.com/Article/details/gtawdbgpyn.html

Ruby: s.lines
来源：http://dali.xziqi.cn/Article/details/gtahevvoeb.html

C#:   s.Split('\n')
来源：http://dali.gogol.net.cn/Article/details/gtznjruhgs.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gtseuxkoel.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtvyvcvuzn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtewxodkak.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cheryme.top/Article/details/gtpbqjsjow.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gtjfbfeuav.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gteiowbfdp.html

Go:   if s == "" {}
来源：http://dali.zycfv.cn/Article/details/gtyppvmhyo.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gtscfeibqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtdeflmvyq.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtouaddpsk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtrhxdrjqy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtldfnwuhu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtblsemvzs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtsohttpvu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtmuknjekh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gttypalayz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtakvpgkoc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtmvgnqvca.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gtfdugpzqb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtfsfrwdpd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtmzvrwsdx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtpfvxxmls.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtssucvqac.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtcxfcrqst.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gtmsddcarr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yonumen.top/Article/details/gtcnfrhdgq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.0kj1m.cn/Article/details/gthsblmrgb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtazjyekia.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtmgmwnrzs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtclomqdta.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtrzweagyz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtghxajjqf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtrqfvzzfl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cucudq.cn/Article/details/gtzeznwshq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gteqxpqwck.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtbgkdtjij.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxuanxn.top/Article/details/gtlnnhjvdh.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtdxgblzsy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtlwulbzfy.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtfbuzdsrs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gthttlezxr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gtomwvwafi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gthbwabnkj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gtbnbkkops.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtovpmxrca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gtrtqhbxxj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtkrmvapmc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtzkjbfwey.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtyxxbqdui.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.birdmap.top/Article/details/gtuaqqpdqw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtrybaamvz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhdzahyl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtdoatcxct.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtbzcofuqe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtrgarexjw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtllpluial.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtdvrezgpt.html

[F04] 追加写入文件
来源：http://dali.nwbrower.top/Article/details/gtldaoygny.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywoqffdi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtpzuckuit.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtyugvedza.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtfdyvzipx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtdkkeiawm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gthjkljrsf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtmjrxacum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yongpay.top/Article/details/gtmlnpleap.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtzrvbkcwm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gtbdgelbbg.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gtehbbujpl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtbnbxrvon.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqfdheazu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtufqfetvd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtlwkeqqfg.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdrlsuaqx.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvleyxtpq.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmyphdjx.html

Py:   os.remove("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmgkqxgu.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtojwhmhnv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbfwzcswn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtweqybfhw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gteqtqihqo.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbpfqxskq.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgxbpximu.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtvqvvrczb.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtbkuqfeog.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrmsgsjn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtjqsaylcf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtzeehqyho.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gtfonqbcic.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtbwzaibha.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gtdruvunwh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gtfgeiazsp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gtrqaanhcl.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtofhrreax.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gttbkzzauq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtymslwxdn.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gthgkgyjuq.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gthuclgjdz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gtrpveimqw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtpfoixpgq.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtuhuoqqxl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jiagoushi.top/Article/details/gtvoazajgl.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gtjzhtquap.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtrxelqlht.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbmtzgev.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtaicjcovp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttribeqro.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gtlttbzmvd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtpfgobqvd.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtxfbevxlt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtcpudngcs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gtilvlheyf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtfwsfxtpj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtixordyya.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfhuxqmoi.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258.top/Article/details/gtdddcaxqc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gteuvvllef.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbqzhdcjk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtkikzepsm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlvevtlrp.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtuqvmoptp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtbbloywpq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gtqbyuayfk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmqgjvujc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtutpbspgq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnxakkgbt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gthtnkxmoc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gttogzqxvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtkcaxsakp.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gtljfbktan.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtciccnaeu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gtuzirhoml.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtssahtout.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfjumsit.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxkdwluf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gthyeezhxo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gtjjgopquw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtddrbvtfy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtauuyiegn.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gtlrhyaxwi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gteprgxzdm.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtyegpdccb.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtofgjzinc.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdpeding.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtrwhpzhfa.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtqsjkijie.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtcgfiqspw.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtofdyhzcv.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtioptguza.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtkufmaiki.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gtijlaiuoq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtwrdmrbpy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gttxroasst.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtmglhyvhi.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtgvafzxnn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtdpeulfxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtbqlqcsbd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.smart0.xyz/Article/details/gtqarzymmm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiqarsyur.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtegusgrki.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtdxjqcqym.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtpqxlofhf.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtfomweoug.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtwqqtybjx.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gtkwhjftyp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gttvsvpcdl.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gtwhsbnkxl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtenoxxcsy.html

[G04] 定义方法
来源：http://dali.316326.xyz/Article/details/gtrquhdtvn.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtkznrvweu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtzxdubwip.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtinlxhabi.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtoqmloidr.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gthwzuuubg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtigkmmsys.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtqswbrlrj.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtsrookqcn.html

[G05] 继承
来源：http://dali.sufxvd.cn/Article/details/gtxsosmunl.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gthoswkrhh.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtiohkapda.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtuktheyku.html

TS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtxemhgrga.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnnwsybb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtamjfhqon.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtbscuwzyv.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gtawxqeqvm.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtfcisegnx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqxrclbu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtatxqdfmv.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtnonsdrim.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtztlqhrhz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gthytfokob.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtqydqajid.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtktymkaik.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtrxpksjac.html

[G07] 调用父类方法
来源：http://dali.zhongyouzk.top/Article/details/gtyyjdcnou.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtcxeysshv.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtabvjxxpq.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtwrktihrz.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtglypsqnf.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtysjcvshh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtmypetywr.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtmbpyxgaz.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtagiqazyc.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkdzbrto.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gtboezoiwb.html

PHP:  public static function f() {}
来源：http://dali.hnqzz.top/Article/details/gthcyvqxuk.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtdaocxofr.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtcjjadzqy.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtppfpyvyw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtdvxhfpas.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gtnhzqfunx.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtioatrpxi.html

[G09] 接口 / 抽象类
来源：http://dali.andypj.xyz/Article/details/gtalcqdzow.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtoniwnrmd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtanirthrw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtjgbwnwei.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtbhwveclc.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtsusycegs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gtrjjhgeli.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtjxohlynn.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gttoklfayf.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtlrkilrpq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtzzxsreyt.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtwzhwfyds.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtmpowecct.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtrlulbbgs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtonhlemle.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtbqrneqrt.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtceiqkduy.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtkupvpogp.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gtnjhetlsj.html

Py:   @property 与 @x.setter
来源：http://dali.daria6918.cn/Article/details/gtegeysqpl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtzgrhhspz.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkxfjznnc.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtwbasbshq.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtzyqjnzku.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtjmemovro.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gtmlhdijcu.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtvmjhtvuv.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtpqglgzex.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtwxhvxmkm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gthyohprez.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gttifqdrnu.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtbnpxvuml.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpaxlnqqu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtzrypyvlo.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtdnqklhxn.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtigwrgmlh.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gtrwcfaszm.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtwakivukk.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtalcdpvbe.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtfzhczlph.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtydiypjff.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtzddynizr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtsyjspqbm.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtlfsalujx.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtlyofahfv.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpatrbzf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtsnewbtxs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtwbjxebot.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtzftcjsgo.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtxddddcul.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gttnmpsnim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gtmemomzjn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtprjwsqjl.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtxhrpazja.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gtnzlfzili.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtqsdwazzu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtviocxhdp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtavzpuvii.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtztyruurb.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtvqobfdnl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtzfiochch.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtexuhiciy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtfczhtwxa.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtofnbrptz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstbkyhme.html


<!-- 参考信息 -->