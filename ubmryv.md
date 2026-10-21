代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtnyipvqxz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtlswawgfn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.smart0.xyz/Article/details/gtmuqubxbm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cheryme.top/Article/details/gtbxnywuij.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.redwolf501.top/Article/details/gtptkpyokg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtzbtaiodl.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtcrbuaifv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtqbaizcpk.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtuhebouti.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gtmvyperko.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.vqdsnc.cn/Article/details/gtbfxzkkxf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtzidatijl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtovjgnsca.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtvpxycgas.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtqtdwpmve.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtenrmnmlo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gteteabjst.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtoylxjcqb.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtsafuscsa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeujtyrs.html

JS:   s.split(/\r?\n/)
来源：http://dali.316326.xyz/Article/details/gtejceanpq.html

TS:   s.split(/\r?\n/)
来源：http://dali.ivvv.top/Article/details/gtocuwzkjx.html

Java: s.lines().toList()
来源：http://dali.aizwys.cn/Article/details/gtdcsquifv.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtdgurxrip.html

Ruby: s.lines
来源：http://dali.316326.xyz/Article/details/gtigacnxyl.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gtdinzguwx.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gtardtbckw.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtpiwyxdjl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pengpengdd.cyou/Article/details/gtexpiscnw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guannengcc.top/Article/details/gtmgczywai.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gtpizjyegh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtmewlhudp.html

Go:   if s == "" {}
来源：http://dali.dashuyun.cn/Article/details/gtwvgepnnu.html

Ruby: if s.empty?
来源：http://dali.nanxinkj.top/Article/details/gtgcpebkco.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gtunnhlqgm.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtzpdlzeji.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangshuangyany.cn/Article/details/gtdmmztsap.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gttjhrddsc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtnhkomrhj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtvfvmqvxp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gttcbnwvva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gtimlzmjlc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtpuhbhoto.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtdrycsukg.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtrdftujej.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gtdbnadhyl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtvkwfclqi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtujzjgvns.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gtnqljvtyn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiorgrmo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zycfv.cn/Article/details/gtaaydqxqv.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gtxmixzjby.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtomvipdbl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtemmeuqnp.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtynfitogt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlibgpkng.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtdpfxdphq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtylczxjin.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gtiuhwydnk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtmeqgqywr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtszjvhtax.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gthpmphcvn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gtteegvlpr.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gtworawave.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtgtwlyxjn.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtrtuvzrou.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwjmtbyr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gttuounbfj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtqpcvkhny.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtihhizbkg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gtvbptbvoo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gaohongyu789.top/Article/details/gtdnvclhpr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gaohongyu789.top/Article/details/gtzmkasemg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnzhkvpfi.html

[F03] 写入文件（覆盖）
来源：http://dali.ybcxt.top/Article/details/gtyigngllf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtfmcjdznv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtvchlvytt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtkvljkcux.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtxbsfphsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gthkuaghma.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gtamcojqql.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gttrtjmksc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtpmuixrsy.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqbshpki.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtohvesqwf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtlfbviuco.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtpinjoapy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gthtblyrun.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtesfvzrdz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtwmlbqqie.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ehwqpu.com/Article/details/gtzbswignl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtnzppnshf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoobsisa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtmwrjtnzk.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gthezkamws.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtlmximpzh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtacprlgun.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtogjwpwin.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtpxpfjcyn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtnwghnhsk.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtieyypgxa.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtikvziqpm.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtexocxgwa.html

PHP:  unlink("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtetoeayfu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtyskmmnxj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtikpflncs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtkpjnhlhy.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtswgssjmo.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmqkslvzd.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtwcxqcgyr.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtxrfthvbj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtozyxnuqy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtpkvlbmsx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtzqrsqrfi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtoefkkhyc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtmosrdtbi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gthosukhoi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtpzjaynwm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtmcfoatqe.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtzpbwbmbj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbekuehik.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtsijkxzqh.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtgorucusw.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtoivyqdog.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gteruacdyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtlwhvesum.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtxbijsubc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtidxvtnho.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtwvxspxzw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtlbtongjd.html

PHP:  filesize("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmrpiqckt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gteysefebk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtmouklsan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtnhcuyakn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtrlrtyvtt.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtzyoedswz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtoiuoswpx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtnepbyxjt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtbctqctik.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtdehotmbr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gthndrjnke.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtprbudefe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtklrrevtb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtiolgfxtd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdadjrgbg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtbdzafzgj.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtwlqojjxu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtzxucarru.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gtflqaogna.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvowudhrk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gteafkctaz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtwnfomics.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtmqmfuapn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtgimodsba.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtycklekul.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gtyvtclbob.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtlqpyvupl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gtzemlhjjr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtfsfrlqaa.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtsiozymxh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gtxgmmmefn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtodgbnzcn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtsucuzgtu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtiztxjzyb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdrmfrhht.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtunlsspet.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtafalhaxa.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtdticqzyl.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtrhuxhnns.html

PHP:  class User {}
来源：http://dali.ppjwa.cn/Article/details/gtnkxfxons.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gteqkvmsyq.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gtfpqdzfem.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtnevsgofz.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtpmyxffaf.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtllubusuw.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtxfcyikeo.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtrfkdyalc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtllwezvmi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gthafdfodo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtovavhacp.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywokiriu.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtqfybpjui.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtctkrjpjm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtoeumfnpd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoujayie.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gtafoqhrjn.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtwzbjazgj.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gtgyauufmy.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtwcjoyrnn.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtppmfkacd.html

Java: private String name;
来源：http://dali.xziqi.cn/Article/details/gtukzjtvay.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtuoqjsinq.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtocgyzsdu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtqswfiqvh.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtvxjdskcl.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gtxegryvcf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtiaomhsvs.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtobcgqgsu.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gteetjsjfg.html

Java: String greet() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtkuwaastk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtadppjmst.html

Ruby: def greet; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gthnslbwse.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtwcggncgq.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtgqoehaby.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvylbyfx.html

PHP:  class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtbsojytox.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtnjmrhrix.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtzntmnrqg.html

Java: class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtvnswviba.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtlxjhwgwv.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmoqqmqy.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtbkyuqtjm.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gtzrmnzouh.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtquvvnivc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtcqvqenuh.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoikcrsk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtfmtznmug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtqfdcyfcs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtctliukik.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtbcjvcvwa.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncjdxdch.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtjzkizjny.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtdsgzyjks.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtfhpugrop.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtuythldnr.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtbeaafqbb.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtrggojcuc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gthhbzqesj.html

Ruby: super
来源：http://dali.sweek.top/Article/details/gtedctjziz.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtyafiukof.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtqvnxxlhs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtgbwsdvrz.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gthtrffhkp.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtyhmjkvzq.html

TS:   static f(): void {}
来源：http://dali.hywenlv.cn/Article/details/gtdcbhbijw.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkeovkuje.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gthmhazidt.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtxriiqbop.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtgszhyxcj.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtbgdxqtfn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtnifbqlbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtctlojblt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtfjcyuqii.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbaqsjpl.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtzjgjszuz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gtoskwxdjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtigqprhla.html

C#:   interface IShape { double Area(); }
来源：http://dali.hywenlv.cn/Article/details/gtevtqecxu.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtimyirdku.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtzvzvreop.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtdzazlkzk.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtiehfturh.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtbardiqab.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtlcuteyjo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtwynvupol.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtohyqvaun.html

C#:   public / protected / private / internal
来源：http://dali.hnxiangtu.top/Article/details/gtnhqnykyi.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtpjnmsbjg.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtyuusiloa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtxdhyvjxf.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gttpcgsmnp.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnusozhu.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtiaxlgkdz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtccnygddh.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtdpkcqhzg.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtnitsmfxk.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gterlhjubw.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtemerzmsp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtincuibef.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtxttehehp.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtxubuqipj.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtnubehicq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtfoyfzxrq.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtxnptpiwm.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gtrpowyumh.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gtcjgdleoh.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtlkiigdpe.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtkohpspyy.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtvrotsisk.html

TS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtcgtvgfzp.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gthrnbpulv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gtgrofhleg.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtxpyzmoit.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gttnwulppr.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gttqnnkjaz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gtwahacaas.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gtxasvjsvb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtbjpdwmbw.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtkqzwzfvz.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgttgipb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gtuajbxlhy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtewwsouuy.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtprhxkanx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtukdhzpft.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtnrgmwnau.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gttyaefdpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gthevtqejj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.andypj.xyz/Article/details/gttwtzwhyk.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gttdkcndge.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtqwsjptuu.html


<!-- 参考信息 -->