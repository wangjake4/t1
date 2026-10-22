代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sxryk.cn/Article/details/gt2yxfmiymi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2ksiymmah.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sufxvd.cn/Article/details/gt2xhkjeijq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dojahuuw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gt2bgojdniu.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.meibo888.top/Article/details/gt2pegxhwrv.html

Ruby: s.capitalize
来源：http://dali.xuanzx.com/Article/details/gt2zuugmptn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvhaqtjt.html

[E18] 模板占位符替换
来源：http://dali.ehwqpu.com/Article/details/gt2gbkdepey.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dashuyun.cn/Article/details/gt2vlbvmpdg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2wlllheyt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwtgzsmi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gt2ehlxrash.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2ydckyoie.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2whixtfav.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gt2kaxazfta.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.mhx1999.top/Article/details/gt2faqromeu.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2gajgmish.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2iivecfaq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2nxrxxvaj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gt2ievbfuap.html

TS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2fwpxsxyf.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gt2nocokkdl.html

Go:   strings.Split(s, "\n")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yghjramz.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gt2kzpttkph.html

C#:   s.Split('\n')
来源：http://dali.guowangkeji.top/Article/details/gt2natntibq.html

[E20] 判断字符串是否为空
来源：http://dali.shuidangran.top/Article/details/gt2kfdtwogy.html

Py:   if not s:
来源：http://dali.tianlin.xyz/Article/details/gt2lmgqajyt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gt2uihxxrsd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fzhhl.top/Article/details/gt2glenjifh.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jusioves.html

Java: if (s.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2klrtkams.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gt2zzlpvbfr.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2nrakgfnl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jruiyvzt.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hukcgvfi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gt2hzmdhikw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2awslymtl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vednbbqe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.redwolf501.top/Article/details/gt2jrszdmnm.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2oxhztyvk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mshwkbbp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2lzpppmqp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2oudeurqn.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hivtbjgh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.aibaodan.cn/Article/details/gt2jinshhwu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2olprzlqf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2evurxntg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gt2xrsheesy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ydzc1.top/Article/details/gt2gladtiey.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2dtkoudhi.html

Ruby: s.bytesize;  s.length
来源：http://dali.cdnleiting.top/Article/details/gt2jsmosbpz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avylcrbn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2crflcopn.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2kccnknsh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2rosyfxlg.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2rnodheez.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nefgeigi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2amunyvzq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gt2thjkycgy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvtiuxyx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2rjfbizsr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gt2nakytoex.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2vmnujphi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2nyuiexmj.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2evafnxsv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shuidangran.top/Article/details/gt2roirmevg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ibupgssl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2qwhhmpum.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2eaoggqrr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2vuldtwfe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2xbmiwxgd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gt2jjmxcgtr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ydqiqdht.html

[F03] 写入文件（覆盖）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqozicli.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nwbrower.top/Article/details/gt2prfullcp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2ngomhfut.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2lfqctmmm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2bwlkgjne.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gt2xsqojpju.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gt2sjejoaxf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gt2yenmpede.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gt2qzhdabvw.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2hmbvoicu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2xxinwxkc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2wodfcsbu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2dzcyxtdj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xylfe.cn/Article/details/gt2xvfpwxga.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2szpuiilh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2nphxumuk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfoanyqi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2rkspgckw.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2tdhhfsdu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gaohongyu789.top/Article/details/gt2yrhcceid.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2zpwygpst.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2dyqqneas.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2lnrsbogy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2oieurtzn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2mpagpqrh.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ovyciwlx.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heeadpca.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gt2leahrbrb.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2wjylhwbo.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2jcukvubf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2upwuefzw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tirrocrv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gt2ybidpana.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2itnojhux.html

Ruby: File.delete("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2csopdbbo.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2hxgnytdj.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyqbupxm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gt2lsaccpqn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gt2rytgfylz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2ksebwbqd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrpazwwm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gt2wltpfmkc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2imbjvldc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gt2iwbviueb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gt2ggjrwppw.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2oqazlmnd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2sfwzowku.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbvkolso.html

JS:   fs.readdirSync("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2vvfeekkv.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2zeukynii.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2ivulpdkx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2xrdzcqfr.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2uglojgzi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppussqfv.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gt2sxyiglft.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2hscavqkh.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2aupwbdmm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2mophhuyk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gt2knvfbckx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2vopbggto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gt2pnblgzxr.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wjplwvdj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gt2qcdlfamm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.aibaodan.cn/Article/details/gt2ybcgsrut.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2kesgdncy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2xzxcwuzf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nmgnjjub.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2gohkoyht.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gt2syclwyji.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2rwftsszm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2zsftqelt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2sguokmgj.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2unslwttr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2cynpoutt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gt2zlwarhnz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2pexagmjo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2xnliawal.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2dafhttbi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gt2ybaqughb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2gebbiozg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2xdvingdg.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2kbwfaydi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gzhubu.top/Article/details/gt2qsbfrxiu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2urefnvlg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbpiocna.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2qsutrxxb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gt2vlogomdt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gt2jhhkaelk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2hybvgozc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gt2pjmivfbw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2xlugqztb.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2phccgvtc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2satbwzad.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gt2hibzbujc.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2yqkkpxie.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2uquoojuq.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2cpukceug.html

TS:   class User { name: string = ""; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jzpgiroi.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fuderrsz.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gt2elsvfyxr.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gt2sqgvnrcb.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gt2cuqeszit.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2bpvjyeqm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2lcgsycio.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2sopsrxqq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hskhwuqq.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2bcgwcgxn.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qwdfucwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2yvgwljym.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emsgxskn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxjgsyao.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjhcbxeo.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2ymqukifw.html

PHP:  public string $name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2mthkurds.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2jscceeup.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2upcaxzyn.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gt2ocwdvtzn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtuyekpp.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gt2shukhnms.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2kuznljng.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gt2fuqnuzcv.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2asmqoihw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2wjmegloh.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2jthkczet.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2bxwcbvpj.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxmijhcr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2tpplxwuv.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2zbmxyedh.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfgaljcf.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2yvkwrmsr.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gt2cpgqrxuv.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2tiacgwch.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvvcfhqh.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2sfquuuyk.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2vpxxqfol.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gt2yzbzxzbv.html

Ruby: class Admin < User; end
来源：http://dali.meibo888.top/Article/details/gt2syhegpof.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2cwlcldee.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gt2puqgeygu.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2rbxqwtil.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rgvblyzw.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2isnooudl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ldwggemv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2skjqjomz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpijemba.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gt2nrsmflce.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2qlutkkyz.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnpsxxcb.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gt2dswlcetr.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngrvvlru.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knpgiksd.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2bszoetfm.html

Java: super.greet();
来源：http://dali.pycfn.com/Article/details/gt2mwfeeljf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gt2fwqoyqnn.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gt2ijgqsbou.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2fiyomcho.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2qmcuorad.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2qisxllfs.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2vylofaok.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkpyggne.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2liqwzinq.html

Java: static void f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2hkwbqcia.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2uafemnbg.html

Ruby: def self.f; end
来源：http://dali.yj20258.top/Article/details/gt2zcskjeeh.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2svsjuwjo.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2plpbwmmu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2emydifiq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gt2pqlsfvwa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2ptrrfafh.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2oxmcorhm.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2whqrutoi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gt2tnilgbyq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gt2dcwnnkqd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aopudsbq.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gt2kuqkyeqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gt2dccusrtd.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2dxutfcez.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiufpztu.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2fxfgwykj.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gt2gawjreep.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2mfqtxfcq.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2jiczmsvu.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gt2dhkrqjmm.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gt2qqartxeu.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gt2uafuimri.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2ulzrysdq.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2btufwsra.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2qsagxkff.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2qpziqlhd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2ymjngaro.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2nsozadwc.html

C#:   public string Name { get; set; }
来源：http://dali.gotoacloud.top/Article/details/gt2pnczxpah.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2dvtmyfey.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gt2apqizooi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyatpoen.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2odnnpadc.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjtzbfz.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cmjfnroi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2orkueazi.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2nsxdozeo.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2nzrlfqtt.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2spiwaqbm.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2hevggjrt.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2yadynxji.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2mtigaprq.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2qsfegjdw.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2kgmezejd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gt2amfwtupo.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2ugbwmdal.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2jxttjsws.html

[G14] 数据类 / record
来源：http://dali.yanxiufei.cn/Article/details/gt2ldluczfw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gt2wqjnybqf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2actbhcvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2mbmvawdy.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gt2onabqnrc.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2fhrolmdi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2xkzbetpm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gilfjnhl.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gt2lelvknfc.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2pafidgfr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gt2kvhbednr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntnvfnzx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2kcgwmnzv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2xdcrlvsi.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gt2ibxqllbk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2qbtwwjeo.html


<!-- 参考信息 -->