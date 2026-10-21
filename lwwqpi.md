代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gtxzympxdg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gtftkccdrs.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gtpidfqkub.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtjsvgbwmu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zdqjudy.top/Article/details/gttnmtnhak.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtztczcbdi.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ehwqpu.com/Article/details/gtwtipvaiw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtbpjrdcrs.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtfhbdipqq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtnurmqrcn.html

Ruby: s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtozcyaovk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cucudq.cn/Article/details/gtmilmhwnc.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtbndodylt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xuanzx.com/Article/details/gtilajslgf.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.andypj.xyz/Article/details/gtnyimuins.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gttecxtfzn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtuetaztzd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gttfjtrhec.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtqzrrmgqx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gtfbbvvgfb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.wangshuangyany.cn/Article/details/gtztatfkvq.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtorjgwqod.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtgykolwyn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gttydidvrt.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhqmnnxu.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gttluwervk.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtyisofroi.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtepilbrzd.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtbrktdidh.html

C#:   s.Split('\n')
来源：http://dali.jlsjyb.cn/Article/details/gthuvzzfag.html

[E20] 判断字符串是否为空
来源：http://dali.ppjwa.cn/Article/details/gtitbwmiti.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtygfwjoez.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gtakhoxsfb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtfmtcxwyp.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gtjxzladuq.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblcgjizw.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gtgxwhkndz.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtxvrkbttf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gtspsmhofz.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gttfrkjcba.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nwbrower.top/Article/details/gtnywlkrvg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtqblwhwhr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtbflbtcup.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtnowdlgks.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gtxjqdpbuh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.iojbl.cn/Article/details/gtvbhgqcsa.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtdrtshdym.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtvpumrqby.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtactjhjrq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jianghu66.top/Article/details/gtxkxnncxf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gthxqfvgxf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnjixetb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtfcpogluk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtrstgwqhl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtckaqfljh.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtqhlrmikc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtqylwbnlg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrhtzcjcq.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtviqapncm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvsfmkvrz.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gthwopqmcm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.mhx1999.top/Article/details/gtpcsebmtq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtbzaofgry.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhsnchgd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtjlqrgmcp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gttasadors.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtwshnmwaw.html

Ruby: File.read("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtialovduy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtiaftephx.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtqgukbthl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cheryme.top/Article/details/gtoenntyzm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsdbwinf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtuhnpwmuv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gttdanoatr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jlsjyb.cn/Article/details/gtpkqlntcj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtqrhlclpj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtvttyicen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrfoqabm.html

[F03] 写入文件（覆盖）
来源：http://dali.xuanzx.com/Article/details/gtrboqgfqn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj202588.top/Article/details/gtiirqdshf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtieinipjg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtqyosqifn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtjtgxrhsf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtsgrduadi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtsnfmnvqv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtpdmwddyb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtduckxmtt.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gtwaykizjo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gtvwlebvwe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gtuewrqxgt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhoezbrl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtcfeqikpu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gtkcnwsxtc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gtdnqruzpp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtnxrdasuy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtvgaxspcf.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtppsxxuae.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gthtmuxffi.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gteyysajfi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtjpyonjto.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzamyqxof.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbrageip.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gtmeoahwyu.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtrqvwakqr.html

C#:   File.Exists("a.txt")
来源：http://dali.sweek.top/Article/details/gthdkvngvq.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtldmvbaya.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtecrpldob.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtjzdhdphp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtcycbfekn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtzgbhimee.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzedrdhe.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gthcmqixhn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxhlvbien.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtfyrpinum.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtchrvpzmu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtlqmnxfgs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtbiiditqr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtpltxsryf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtdmznjqwk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gtsgxhtgfn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtyccrrzxe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtsvwwacnz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtgrkhivyw.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtqqolvcdd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtxywbicds.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtrvetdiri.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gticscpjuz.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtchdglwgt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtisduzmcv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigufen.top/Article/details/gtzocmjsjs.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtrmmhpdmf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtojzwbdmq.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtabegaqkf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjrmljcqp.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtoroqcode.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtdivdwooj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtxwgheaan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gthjklncmp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtcvxmoikm.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gttuxujaax.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtuishcphz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gteohnbexb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtatfaywyi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtcnjuzhze.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvloleukk.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnfhscmju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtluuxygpv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqefztzz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtzfgrbbcw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtrmikfjqt.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtxyheqapu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtncttjfxo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtjpserkff.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtnifnrpda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtqeflrszq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtxefitcoq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gtnewkmwkd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtptrgwgbq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.mhx1999.top/Article/details/gtgfhljkbl.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtcrxmpqkt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gtkhcxfrjl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gttfoflogc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtzuenpqfh.html

TS:   // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtehdtpmtu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtnhoarnyo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtxbhxvzwk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtmvediwcz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssiwlatt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttopgncio.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gtnjdxxvdp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqszjnqcc.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gthhrgszgq.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtdlkmspfo.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtpfqmksmk.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gtqxqttwer.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtimnrydhw.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtnfuxmqjj.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtkchfnrjr.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtqyrzhwzu.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtaoodlodf.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtoysfphzw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtsrcnbnwv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtssvadqsy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtivziihzj.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtjjvxncuw.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvztueywl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtcwohvfin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtbbnaqlaz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hammf.cn/Article/details/gtkmesxkqn.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtfagtzhsz.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtbqitwgyl.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtyzzsogfs.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtefuvqqov.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfrijizc.html

Java: private String name;
来源：http://dali.meibo888.top/Article/details/gtstjkzyno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gthgyazdzr.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtpbgciypy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtpwnoszws.html

[G04] 定义方法
来源：http://dali.redwolf501.top/Article/details/gtlbhuszdh.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtdqrgaakx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtiklsdpsn.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxssoqwwj.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtptzuztgr.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtssnxfkpy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtqtqkqurf.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtqyyqikun.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtzzkrxfjt.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtzqiarvfs.html

Py:   class Admin(User): pass
来源：http://dali.feifeiyinyue.top/Article/details/gttnrkmwmr.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtwaxwooff.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gttjqzlcfo.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwbmwcbli.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvgnsxlyo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dashuyun.cn/Article/details/gtrhmodjsp.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtttsoixpg.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtlochryhy.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gtiaabhofh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdozkgbsv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmgkijcf.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtklqyawoz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtmwcfwzyq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexpvbck.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtmbbipaej.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtbpdphmtv.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gtqbknxazh.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gttucccqeo.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtkrhuaeab.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gttkwthfhl.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtjfyxrtsk.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtfaiqspww.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtwcjhpfqi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtlsgdlzhj.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtaefedotv.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtyapevivo.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtlwpiaozc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shangyingyoupin.top/Article/details/gtznvroidy.html

PHP:  public static function f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtksvjlxsg.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtimrzuztx.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtgnzzzflq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtfavnzljp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtgcfcyowz.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtzmrqycfg.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtvmcvytbd.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtforgiznc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtoivusoss.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtcjwjslvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtclqxfely.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygxcqdpd.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtczcyhmcu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtszgnmqzd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtbkbsfngm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtanwcprsu.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtzdzqwfom.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtiykiyeqe.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtexlujzeb.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gthzsazoga.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtiqnkicbc.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtnwamzkfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtllzumeil.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtzvqgiosn.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtbzxafvaw.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gtydccufcf.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gtrsyihyrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtqvunjbjq.html

JS:   get name() { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtqoyfflti.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtcrldqpxk.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gthvfinlzw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtcbylghve.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtufvvldcs.html

C#:   public string Name { get; set; }
来源：http://dali.tanke756.top/Article/details/gtyircemii.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtmycfhwph.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gthcdanuvx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtcmubflko.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtvqwbapcp.html

TS:   toString(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvpjgwkm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmdthlob.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtdbacmxsu.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtjufoiwrk.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtmwbistrd.html

[G13] 判断对象类型
来源：http://dali.zhixingplan.top/Article/details/gtwviopgyk.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftqxesod.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gthhrcdien.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtuezjpqsy.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtpuvajdmn.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmifxvhnk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtgrehdrop.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtzyteftlk.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gthnmvxdwm.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtuhbuoshr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtdewjcdvs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtdmxeoeiz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtldxqxgam.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gtohrwurfb.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtnexzueoj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtlfygazrj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gtznyeobtg.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtplcecplf.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtzwxpoadp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtecbaeuye.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxynnfdhx.html


<!-- 参考信息 -->