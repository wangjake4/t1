代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gtokazpndc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.kuanghao11.cn/Article/details/gteaimmrmq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtziuwtlpj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gtuzaqegey.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnlbtetit.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aibaodan.cn/Article/details/gtxyzidimj.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtmeqpagce.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.pengpengdd.cyou/Article/details/gtyvzaxgdl.html

[E18] 模板占位符替换
来源：http://dali.snrcjt.cn/Article/details/gtjtmxfhhf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtjqnclpwf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ppjwa.cn/Article/details/gtaqoomjxe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtmdqwbyux.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtkgabmnhg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtunxedwek.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtvjstpevq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtjqvewntf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gtcdkjwclg.html

[E19] 多行文本按行拆分
来源：http://dali.wangdashe.top/Article/details/gttbqgqzmk.html

Py:   s.splitlines()
来源：http://dali.cucudq.cn/Article/details/gtpwjvjtow.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtgnhaddjq.html

JS:   s.split(/\r?\n/)
来源：http://dali.sysykeji.top/Article/details/gtvlamkgyp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtjjcioyvj.html

Java: s.lines().toList()
来源：http://dali.0kj1m.cn/Article/details/gtynqcidap.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gtuhtzxxvz.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtlxipcnox.html

C#:   s.Split('\n')
来源：http://dali.yuxming.cn/Article/details/gtadovqekg.html

[E20] 判断字符串是否为空
来源：http://dali.gotoacloud.top/Article/details/gtswzxinqs.html

Py:   if not s:
来源：http://dali.cucudq.cn/Article/details/gtjaixpuvz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtvokkywft.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gteibwcwpw.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtsghgdfbc.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gtnltbtorv.html

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gtpsyefrzo.html

Ruby: if s.empty?
来源：http://dali.guowangkeji.top/Article/details/gthfjxmeio.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtameggkne.html

[E21] 超长截断加省略号
来源：http://dali.daxiang520.top/Article/details/gtgxglazlw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenzaomai.com/Article/details/gtjocruccm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtmypqzale.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtlwhdqehe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtxysbvgbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtxybahhnh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gtqhvcxlge.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtfcbkbzii.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtxmqrzicc.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtlgstgxbu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtkzujazaz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmxzvlew.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtgqcjfrfh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtfwqzcuwy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtztykqfzl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtbryjdbqa.html

Ruby: s.bytesize;  s.length
来源：http://dali.sxryk.cn/Article/details/gtquxhsdos.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gthswmsfsk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzksqvwuj.html

F. 文件与目录
来源：http://dali.yvedp.cn/Article/details/gtbqzcvhhz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfpywdkvd.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtairfncgw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtyclpbzbm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtgkbpmrls.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gtmmigxzlp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.fzhhl.top/Article/details/gtfjhipnje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtzwocnuym.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtvctgczfa.html

Ruby: File.read("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtoripwkko.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtgikwupfz.html

[F02] 逐行读取文件
来源：http://dali.0kj1m.cn/Article/details/gtipcdyfzw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtfwakdcxl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtgwmwcvqe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtpeferhbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtbyhmbzrd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtsgshsbec.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ehwqpu.com/Article/details/gtfrguidaz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gtrdxexzov.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtqqkyweti.html

[F03] 写入文件（覆盖）
来源：http://dali.gotoacloud.top/Article/details/gttotrshjg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtxydyutkl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtuokotoxj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtopqtedps.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtigoypyfp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtztxojqqa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.andypj.xyz/Article/details/gtpqwfdbsz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtthkrpiqf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtydofjqfj.html

[F04] 追加写入文件
来源：http://dali.yvedp.cn/Article/details/gtwzoiqspm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gturejmkwd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtvvvvwsev.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfdpvlju.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtwqommmub.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqgtjakl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtysixqmzh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvrggyxz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtoberyjdm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtibuwasli.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtembrvzfl.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtymhvfxoy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqbmpzypl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnjceutcq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtnhirmxjm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.quarkkingdee.top/Article/details/gtfggoczsq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfyzaguia.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtasbnmymj.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtkemobqrm.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqxcqtmk.html

PHP:  unlink("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtgtslrylb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtiostiylp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gthaengsxh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtrwvznutz.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gthgehiqcx.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgmxwiezm.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttkarordk.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtdzseuqcs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtbrnqhywi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtetewaoyu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtwgorpjlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtlgsqznww.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gtgzmxqwcd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gthsbgxqxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtrduugpft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gtkvknbzap.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtbbqizjsc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtdilfnzlt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxzqoypx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtudictfms.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtedcvzgqy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfgyadat.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gtvyojlxxc.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtoquecyhr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtvtjyzsuy.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtvsrodlqd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtjymqgqij.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtbkofurnc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtzepfoiow.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtuuadhoar.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gthvgnrrrv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtvupigbdr.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtxpketeki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gtqkaimwft.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hongshengwenyu.top/Article/details/gtreeufadp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtargnrnoh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtehfcvnmx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtefaqrbyl.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkmogocnb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtvmvqeozj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnhqncsts.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtitmjhtlq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxuyxxbgk.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gtavtufrpn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtltsbpcpe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gtxhacftyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtypopaqhp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtnjugxopb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtjknvkixt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtxnomhcky.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtqlnehbxo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtfpwpsijr.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhuhqcsv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gthqwnzqfc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtetbvetet.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gthetowqes.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtgccossgb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtqmazngds.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtzaklwafa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtokezryve.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gtjnkphvng.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqrrilksb.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdhjqwnr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttzejbfyv.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtvvbydbdh.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtfyxjurzg.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtdaeobnyp.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtxmofrass.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gtacrucnjd.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gtptnkobkf.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtiwrqwteg.html

Ruby: class User; end
来源：http://dali.sysykeji.top/Article/details/gtwvottlni.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbnodrgm.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gttxwlxtxj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gtllvqoqse.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gtnxlkhpwf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtjyhdncfr.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirccdzfc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtrotbzznq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtlfiibgnb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gtoimduglk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtssxwuyii.html

[G03] 实例属性
来源：http://dali.zdqjudy.top/Article/details/gtpnpmopoo.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtgbsgeuhk.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtawhxyqyg.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtfjtmbien.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gttvwqjhea.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gtjlkqvcra.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtaggxyvzk.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gttxcfenbt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gtrvzxqfxd.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtrpsdqnkj.html

Py:   def greet(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwullxzw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtrogfbnno.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtqkthmyhm.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtatopdqpt.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmxfbymhc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtsdfmxlyq.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtfmtufziw.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtxftcmibn.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtsupnxckd.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gtucbiahwt.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gttzfilujg.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtteckylde.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtttojovyj.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtacctgsji.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtdgorhxol.html

Ruby: class Admin < User; end
来源：http://dali.zhixingplan.top/Article/details/gteazxjsne.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtjyjqfssg.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtqimgjxvy.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtdzegdzmy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtlcrbmimk.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtsuxlugzk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuaznuiuz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtwxnckaib.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydjjiyvp.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gttwysfttv.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtsqrpiuty.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtracvxrjy.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtnxzsfedf.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtwugfblgn.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuhpmptv.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtndqhntxa.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtvtoegqjv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtqkapuzij.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtmaegbxch.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtnxzqmuwr.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtdzpbvzoq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gtkslneltb.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgowejhv.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtfrfhbetp.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtgrbwzwdb.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtnhkcrhld.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gthpmfguiq.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtnvjyxdyy.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtxwtgcwdj.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscrxlmib.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtumdhwcoq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtnbbxjlxm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gthswkleph.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtaxhsqsru.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtpjvzwfvo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtkhvwoimd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtwkiqlexo.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtnshnatut.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtfdaavwtq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtwhszqwio.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtnviyekog.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtzlubwquu.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpntykilp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gttknbeewv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtaejnrwxe.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtdgqoccvu.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gttvjdnlir.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtudppnzbg.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtxxiwaont.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwfjkaxa.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtxrgdnkde.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtuutsviqr.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtuplalhap.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtnjhxmnlw.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtgbwgpyhv.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtpzkelkxv.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtqscgiwxd.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtwnyaihal.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtyyfdnxcd.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacbnqncv.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtusmlclxo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtilciagal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtepsykdfa.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtugzkqmyp.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gthrxwxshi.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtmrlbydom.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gtwjswuwub.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtxxhtoxcd.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtkkgaxzxn.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtlmegqcma.html

Java: u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtwsazmjus.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gtwhmiheij.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwiurpon.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtsktmtzxl.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtvrqfcfza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtrfzllaof.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jyoumei.cn/Article/details/gthfyborpd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtnzrnkirx.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtluyspjwv.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtjahdcvyb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtoxfamxut.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtrdbwclyw.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtdfnkmtvc.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtevjnpsmk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dianchejie.cn/Article/details/gtlyvqltqr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtppbzsvlb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gtwslrqhoe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtthzvcsep.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtbvynljkt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnvkbaqe.html


<!-- 参考信息 -->