代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gthcwdwuqh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gtgtdpzjdf.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gthxecmxgo.html

[E17] 首字母大写
来源：http://dali.cqqwz.cn/Article/details/gtyffaqryb.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtsrumvbsr.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ydzc1.top/Article/details/gtrjwnapjh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtruemoxrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gtaswokusw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtjsvxotuy.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtfvsxjtiz.html

Ruby: s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gttflvamit.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtsfjomweg.html

[E18] 模板占位符替换
来源：http://dali.jinqigfzy.top/Article/details/gtlarxuwsr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtqolyvycj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.snrcjt.cn/Article/details/gtiddgqynk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gtjgbpavwc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gtzsbycqha.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtbfwbzchj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtwibfcbdi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtbqwakiui.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yongpay.top/Article/details/gtmpaeepco.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gthbhaqlzu.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gtbxsdbfkc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gtcebpaalf.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtxmwywgur.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtapfcbavv.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gteniyjnzj.html

Go:   strings.Split(s, "\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtqpbfuksm.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtvltmbjok.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtpmaesasg.html

[E20] 判断字符串是否为空
来源：http://dali.gzhubu.top/Article/details/gtwidbdgpa.html

Py:   if not s:
来源：http://dali.aibaodan.cn/Article/details/gtagubuqtb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodkfxpvr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sxryk.cn/Article/details/gtmuiroksi.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtybfznazx.html

Java: if (s.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtuxbdeqxl.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gtyrdhlyqa.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gtelzjwkaj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gtajcdxoeb.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gtwqsdlftw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtvmjwexqo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtzqqwogqe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtfhewjpav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtxmtgwtpp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtsxznmnho.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtkdiimytu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtdxevfezo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtajrebtuw.html

[E22] 字节长度与字符长度
来源：http://dali.nanxinkj.top/Article/details/gtzsfgpmel.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtlfkolajp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtuyuzqahr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258.top/Article/details/gtvsstymvg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtziziaicj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtngmaezfh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtghcyugub.html

Ruby: s.bytesize;  s.length
来源：http://dali.guannengcc.top/Article/details/gtxamtmfrk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtetfiouha.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpdhqrkht.html

F. 文件与目录
来源：http://dali.havefunace.top/Article/details/gtszsnzncc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gturlzsxex.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gtsmykiopt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtxeoktghe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtmnvzdrvb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gtkgbqwwvq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtqckoonpe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtarcgziil.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.iojbl.cn/Article/details/gtcyhrhyny.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtezeqruxq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gthnnvcpfi.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtadnofvck.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtgukjbtrf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtquurkrow.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmudtartb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtmjjmyusb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gttxkijfsn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yuxming.cn/Article/details/gtwbaeaumq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtkmrofppf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.wangdashe.top/Article/details/gtrrdknihn.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtbmnmyhwh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.0kj1m.cn/Article/details/gtysaravor.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtzsshigsf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtlrdmqlxr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtkfphhpqh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.daria6918.cn/Article/details/gtmugxzqsj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gtwxtcmvvl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gtfzogodzp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkmqottx.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtzyxekmsv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtsehhtlxq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtfjeibuxw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxcxijjv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtxbedjofe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nwbrower.top/Article/details/gtaarcptdg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtjybobglz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gtqltnzwbp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtmcldekxl.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtwyowynwy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtiecrseql.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtfyqoakry.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtgfzmayle.html

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtdhxlbtfl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gttivylujy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtcdmwpmdq.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gtafjkczpq.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtrlijskxk.html

[F06] 删除文件
来源：http://dali.hnxiangtu.top/Article/details/gtprnjpzif.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtfykqtpzp.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gthaqytqfx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtngnyrlcb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhujyzzv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gttpdltdlg.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gteulhwxiq.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtvwfdehou.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtkhdjwtdh.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gtyyiipvgp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gtjecuvglm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtlpuuiwkc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtkpicdkun.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtkrfrknrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gtggprifpp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtkcucvzgm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtzdulrexa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtdcbbpcmn.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtdhelalkl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gtoiocypds.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtqvibpupn.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtkqjjwvvo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtetencbtb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ppjwa.cn/Article/details/gttoyvmeuh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtoiycmffm.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtnbfrbakp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtipkmnijl.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtbalytwos.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtccezropo.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtbxlhdphj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtydkbeyzm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtylvepcca.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtjdwjbzgr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtbulubefm.html

Ruby: File.size("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtxunvvghj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.0kj1m.cn/Article/details/gtrcoravmn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtotpfihna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtunomgvpz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtfkqbzorp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibwndbgj.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtynchiaob.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtulfrmhsa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtrghpcacs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtcwcpvsit.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtmzbkgggh.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvbbqythy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtazggxshg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtefrgsdve.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhxnaatn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtfxxdoyim.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtqqivlnbj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtkllmmpzt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbbaevihn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtgzqwlrrf.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtyziwbbia.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtvoaxtibq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtmejfoceh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtppahfcwl.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtyeomrsar.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtjsbqubrc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtimkuvzpe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchwznksn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtmmdplmka.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgqffwcti.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtmadopcws.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnxyltnhb.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtpclpcgoy.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtzerlzwvi.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtatabtjad.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gttlewkygq.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtkzncgkxv.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrafswlfa.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtpfrongwn.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtpjxxeuhy.html

C#:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtjnlbfqas.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtsxyobiak.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtsohikhnz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.haohaochexian.top/Article/details/gthikbzjdz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtjmkmxlpo.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtokqduuiq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtvbuqixsl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtxxycakpb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtiocnyeap.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtxxvvewby.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtfxzjccrq.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gtbhtvrxgq.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtvrbblgwx.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtskxvcyel.html

TS:   name: string = "x";
来源：http://dali.yueranfly.top/Article/details/gtjhhmoing.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtkallzbzf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtboneffhm.html

Ruby: @name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtrjarmpdy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtighnnlli.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtsfpowjbn.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtkwiuxqjj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtlcfegywo.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtsgezgnnm.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtubbxgqxu.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtdmalus.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtkfzzwzhx.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtjificshj.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gthwdtsxhw.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gtojreqpav.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtdmzirvno.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtkuosfxlf.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtkogcltpn.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtslhrfboq.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtaaqxwvgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtzqwmcgum.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtlvqtudgy.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtprbmurjf.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gthrpgrsci.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtbwartfcu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgaeatmre.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtdxywneoj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtfggiyxpw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtrozaelxa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtoegmbzgx.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtetnimgqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueeprxls.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtixjmgffe.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtfthirxep.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtwyvuyczg.html

JS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtbafghrxk.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtqixsszhq.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtlfsnkazy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gtipufrgih.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtctajmaad.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtyjnrjcag.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtnsmidojt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtfpakabfu.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtggssezho.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtzenbylfp.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtrjmnoxrq.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwvnzsyf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtqaihiupe.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtrmvkanhj.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtuexnqlgl.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtfazpscwt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtcksxpqjk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtyhuphhtj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtjriebxrx.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtujfhylec.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtopcgqnqe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtsossgimi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gttynbmexn.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtwunxibip.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gtowwbgkkd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtgdrolpxq.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtrkivyaux.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtctmlnjpd.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtwbxqxeqj.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtairkcacp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gtrtiwyibz.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtwqqiksdr.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtdorvmeyo.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtiepzjabg.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtxmvolczx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtgcmoqeec.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrmsboyfq.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtwkjsxrnp.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtrhxdyzni.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtprwzidus.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccsjwgqu.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtnyvbuxwc.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtrxzgfuwc.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtirlduwsd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtuqaxhigz.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuotbbbt.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtzijekict.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtqbopqsjc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtslbbfjgx.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtxpcmdram.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtkcjauzfc.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gtszyuhyeq.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gtahdxdzzi.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtgvbcxdhv.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtwahglclq.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtitteaaig.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtscrqsugn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gtzzgrwvcy.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gthehnpdkv.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtfityhejz.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtsyuufoyr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtjbnyrveh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtikthdprp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtuyyjwrif.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtyxxnqkcl.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtefmdeezj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gtidnfiels.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.bjfxy.top/Article/details/gthukzaxcz.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtuuzbddsk.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gtsopemrrp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtbgkfptgt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtoevssecg.html


<!-- 参考信息 -->