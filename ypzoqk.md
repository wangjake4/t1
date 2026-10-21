代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gtbbkvargu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gttkkliwph.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gtxzdeqmev.html

[E17] 首字母大写
来源：http://dali.wangdashe.top/Article/details/gtfucyibgg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtwgzuuqkx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.fzhhl.top/Article/details/gtvhxoxkip.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtgpjmymeg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hysaishi.cn/Article/details/gtervnctdx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.kuanghao11.cn/Article/details/gtukpggukq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtcciussao.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gtpuduwbsg.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.wangshuangyany.cn/Article/details/gtgabpnncd.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtzfoyvdoe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsflllbm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gtchceugng.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqbegjwh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwogyjtt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtzzjwkrzp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtnifbrrze.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gtgxlabiav.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sweek.top/Article/details/gtrvwbqfjp.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtrizgzqhm.html

Py:   s.splitlines()
来源：http://dali.cashguo.top/Article/details/gtkadcsndt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigfzy.top/Article/details/gteiiccjlk.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtskvgwger.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtxckodpmh.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtimvqqnqr.html

Go:   strings.Split(s, "\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzgrtibu.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gtkhcubmur.html

C#:   s.Split('\n')
来源：http://dali.nanxuanxn.top/Article/details/gtkzkiznop.html

[E20] 判断字符串是否为空
来源：http://dali.guowangkeji.top/Article/details/gtlebhxkej.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtfqynoggf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.andypj.xyz/Article/details/gttnwslavg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfqafrmam.html

TS:   if (s === "") {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcucovzdw.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtzqelvele.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtehcokjak.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtnsapxpyi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtqgtofxwy.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtiiydvwww.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtqhlyrwum.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtosrvfiio.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gtyadpylyf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtmyjdefew.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuoyftwf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.aizwys.cn/Article/details/gtughnnitd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.redwolf501.top/Article/details/gtntnlphrv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtigtizxcm.html

[E22] 字节长度与字符长度
来源：http://dali.andypj.xyz/Article/details/gtnnlqmmpu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtsdxzgxqs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnccdrpnq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtprpihhvf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.smart0.xyz/Article/details/gtoyocsxme.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtlqsxazze.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtdvmzrvvq.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtwvrxwtzw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtzqmwsfne.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfvmckljs.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtkbgysvkn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyfyngvup.html

[F01] 读取整个文件
来源：http://dali.xziqi.cn/Article/details/gtbbnisort.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtwcnrmgrr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtlewzuhhv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hywenlv.cn/Article/details/gtnjlnaoey.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtaiclvncy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtrkeukiem.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ppjwa.cn/Article/details/gtaoqwpiju.html

Ruby: File.read("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtdkkdkpfi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtmfvpbqop.html

[F02] 逐行读取文件
来源：http://dali.yvedp.cn/Article/details/gtguajwbea.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtexdlsdjl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtbuvlzxgg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gtdpcnobqi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtluyqcakk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gtulrconkh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sufxvd.cn/Article/details/gtwcjkvgqy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtxtthbarz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.daria6918.cn/Article/details/gtijxdjyhk.html

[F03] 写入文件（覆盖）
来源：http://dali.hongshengwenyu.top/Article/details/gtpdhrfgkh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gtuxqyxdxz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtvgrsimyr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtpridmvwx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hammf.cn/Article/details/gtyxkmewtc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtqdfztoci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtmmhuufde.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtsjouzevh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gthnzemgnu.html

[F04] 追加写入文件
来源：http://dali.ehwqpu.com/Article/details/gtvkeevezd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gtszqwugud.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gthvaetxki.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtzsrbljzd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtznnvvhpr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtwtfocyzz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtomsrchdy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtecelpdei.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtatwhykub.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtsiumdqzd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtpbfbcdzt.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtftououxo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gturgpytng.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtsgbpsjys.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gttpmpvyrp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtmwwnpqdo.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtofxysqxy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbncsjvo.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gttavqyump.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnvjsios.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtwfbvitci.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtciwuootf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtjadjpdjr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtayvrzzzt.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthjdgcczs.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtxeegweie.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gtyffynzpn.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwqtglvf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtgenhjspn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gtetlnzjcb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtdplqazua.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtazubrzdc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtnjbmmvdf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtxcafekzq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtnpucjtby.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtafcuhpit.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtxhupjppr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtaqfzxeyh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtwbideetd.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtdqiywbhz.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtqhtnfbpx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqscjsld.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gtuvcdbsyg.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gtuvcqqgqi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtkvrqffjm.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtfqlvdvoe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtcloptnek.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtvycuczrk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtbfyadowq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtchdmcgtq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtnqsmmnqv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtlsjhsljt.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcivsthcy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmbgopwf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtlpqvfruv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtsvszhmrk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gtpanxvqfu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtyqjjefgg.html

TS:   path.extname("a.txt")
来源：http://dali.316326.xyz/Article/details/gtaemxnqyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtflnzrcsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrujqcjzp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkuxrntrz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmsszojtv.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtlcolxtoa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtmcoafspx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gthsqivxdw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtiyooatlt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtedasewjd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gteufxeanv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtpnjeooov.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfpzeubuv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gttzedfcyv.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtrvnobicz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtghbgrdot.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gtxhnztcjl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtzvspfjpj.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gthviigqid.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gtfmssxvep.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gtogxpbdlo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtpgpsapvb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtqzghfuul.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlukvhuto.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtakqzspug.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtaxevaofk.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtdfylwibt.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtznujmvyx.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtntqorzlf.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtgyhnqtfh.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtndansove.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtsidsxltj.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtoeuyugnb.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtwotlhkfp.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtfejdeydq.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtrrhylgds.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtbapawwah.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtovflvknk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gthttdezda.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gtcewnizqo.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtsiiqthwh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtzimxqoyk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gtgvpezawe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdogkpofj.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtckitjqtg.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtmxmxeqhi.html

PHP:  public string $name = "x";
来源：http://dali.yueranfly.top/Article/details/gtvhtuhppu.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtntulrkye.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtnlbsuyyj.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gthvninlkt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gthndfwxzq.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtmjbbaieo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgfzy.top/Article/details/gttehaklfj.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtaeoqzgar.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtgvslbzit.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqcvhyxua.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtmqpboety.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtmqzduxhf.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtfncsojhi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtczjqpgoq.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtiuvqejkn.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtxbsiqvwt.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtibdhzjir.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gtahsrknqa.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkxpzvlut.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtrujaiggc.html

TS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtvnnwiewo.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gthfrpilud.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtxntwkayv.html

Ruby: class Admin < User; end
来源：http://dali.gotoacloud.top/Article/details/gtnsbrabaq.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtepdafych.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtcybtfcrf.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehspqbqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtyqoqocrn.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnbjijds.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtcotwpcoy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtqhlflsfn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtuqcyhloh.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtpfyvtmmc.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtygagaimq.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcpgqesa.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtgqqxrdas.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtcimsmqpi.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtnrvfdrry.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtxwyngwuw.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtvhrairyq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujlsjekl.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gtowofuekr.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gthmnhatnq.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtyknglbvj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtyzdinjnz.html

PHP:  public static function f() {}
来源：http://dali.shzxlz.cn/Article/details/gtbkinxxut.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpdggkvlq.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gthhacrstc.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzmoonbms.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtosyaqdca.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtefkssyqq.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtueynivfm.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtcnaogegp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gthooveuvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtresptkml.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtdxcwaavw.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtaimgclxq.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtnexlsrza.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtztgauzxv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtdjhwumch.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gtecibxfhc.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtolfyhyht.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtzjqhqcul.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtkqdgidkh.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqxcykbz.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtnvpksmiz.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gteqxosvvt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtpazdhdyv.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtgzowxlop.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtbujfnrur.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtqeklselz.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gthwtjgjsq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtqxhwzukb.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtprngsspc.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gthuotrrnx.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtvehoukum.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtjmqciobk.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtgcrfxyam.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtgyhlwvff.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtewafsdws.html

Py:   def __str__(self): return self.name
来源：http://dali.tanke756.top/Article/details/gtduhpupue.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtuuowxsor.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtyxsswfwo.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtzqvoyyaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gteybxxgbh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtvrkoygdz.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtxuibeiks.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtfrgrknnz.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtuszljscm.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtnxhsuvfx.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gttijctiss.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtnnhcqawy.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtyhwjsdrp.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtafqwaqxy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtdmnclxpv.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtpghwizkw.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtmpvkxhur.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtnefhjfwr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtxzmfcssk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtymqmrfsd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.aibaodan.cn/Article/details/gthaqffnru.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gthjtasqsc.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwamudivr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtjwnsrqme.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtskubfhpj.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gteytzzksu.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtckvidqgr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtfmtjxlta.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtfmdbzmox.html


<!-- 参考信息 -->