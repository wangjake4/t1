代发 wailian999

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2kubmfedm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gt2xwdskzdl.html

Ruby: s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gt2hitbdcxk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2swdudbro.html

[E18] 模板占位符替换
来源：http://dali.cheryme.top/Article/details/gt2vyebdlvq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.meibo888.top/Article/details/gt2lsoibngq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gt2hhlqdujz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2xihyniaf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gt2nboiitdq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2yntjtywd.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2mhccwoph.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewscmxvo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yj20258.top/Article/details/gt2xhvragwa.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2iropplnb.html

Py:   s.splitlines()
来源：http://dali.nanxuanxn.top/Article/details/gt2tspzgchp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2xorfkxxp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhiggvt.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gt2wtzufhge.html

Java: s.lines().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjewdsjs.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2dmimoatv.html

Ruby: s.lines
来源：http://dali.snrcjt.cn/Article/details/gt2kzojdmev.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gt2pzqulymc.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gt2ztyrhnbv.html

Py:   if not s:
来源：http://dali.xuanzx.com/Article/details/gt2llxjfitx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nwbrower.top/Article/details/gt2njrcesch.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldbjxuyu.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2yfmkbusv.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2eilvhffn.html

Go:   if s == "" {}
来源：http://dali.tianlin.xyz/Article/details/gt2jkznaucl.html

Ruby: if s.empty?
来源：http://dali.shangyingyoupin.top/Article/details/gt2enfeqfye.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gt2aoxwiczp.html

[E21] 超长截断加省略号
来源：http://dali.tanke756.top/Article/details/gt2bnktinhi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gt2ednmibrv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2uklocsdj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2fucwsjrf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2kywjvnne.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2bhixkngf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.haohaochexian.top/Article/details/gt2pzcwttze.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2qnrtziqm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2ecxwojuq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2olhinlvi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gt2oancugcg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2gvuoilas.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2eevjstnx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gt2aclygqqo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yuxming.cn/Article/details/gt2fqywxpfl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gt2zmhedyol.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2vhjrlije.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2vndaxvyl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2wbelfoox.html

F. 文件与目录
来源：http://dali.meibo888.top/Article/details/gt2nofipjey.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ceroigsj.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2zvnohhsu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.svipenyu.cn/Article/details/gt2icdysrgo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2iaojelme.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gt2crwhzgtd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gt2boxdqzmw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptyemgym.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gt2uodmjbas.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfuscwyn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2okdsrnhr.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2vmteluou.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2knfaynlv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2gmxnyolz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2tgunpnkr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2pawsdkgy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2mjlgmhuw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gt2fjnkjshh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangdashe.top/Article/details/gt2gkbrjnrb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gt2qrqxduzw.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2aczvhkpe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gt2zeolzmkt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gt2ifvghgdo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzwvjiqc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2yyfovjzn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gt2avtjbtud.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2ssokowps.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbdyysug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtgpvpns.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gt2drpgauam.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2zxzssycb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gt2foylybin.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2eqvhtday.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2vwsyvogz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yangfankeji.com/Article/details/gt2ulfewelo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2uyiuzxyl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncbroguc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2bihdjbtq.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2adoifpto.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2unxztxch.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2exxvmtgi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2kmrisudn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2aguiowsh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2asisqywt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2pcayprup.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ddojqdov.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2czokrwnb.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2clhxnrmz.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ajzotbak.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2qwfibivp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2jwwygrwl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dxzzknyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2ajobfutn.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2csclvnph.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2zfjcrdma.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2micxtbqu.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gt2dzuijmyc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2hykcxbuk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2qebqmcmb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2gzrdnsxw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2elnunmik.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2qirhmcuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gt2qdanadxl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gt2rhxkjkbs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gt2zadvcheb.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2xhfxxutm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkudrpsv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gt2rykuyjmw.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2uxwndyxc.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2liguihyz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2ljdvocga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2pnzfvyos.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gptvhzwg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2gagqbssh.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2xcoxlyoe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2vwdbsvlq.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2hwnyggcw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2flidzgcu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2kqvvyrjj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2opmxemnf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asoicykj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skstgwke.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2wjxrxwpe.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdrydnhx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zosjplqh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2rkbfurqi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2meweplae.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqtxscxk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gt2drfbwins.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2qbrxpvsk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2ssszkjka.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gt2ecykcphr.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gt2dthrelhf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ynzhhktg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2cdefxzqd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2rlqvemul.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2iizucwds.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2hcdvpcmi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2cewoiecw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2botrvorw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hterzlyi.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gt2vgfycsyt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gt2qclbcgkn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2irjwltoh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2kbyptttt.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebidywbv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnqzz.top/Article/details/gt2vfuqjuvs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2svrwzzbe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2xspvbhor.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gt2pqfouhzv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2aklagtsv.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2diyjtbsp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2rlfyrwpa.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gt2cueavoli.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gt2akytlmae.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fxstgqnc.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2altlpmib.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gt2mavhchvu.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2hbkbafoc.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gt2sztovhzv.html

Ruby: class User; end
来源：http://dali.fengsongda.top/Article/details/gt2zfprohng.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gt2qdjcpvhv.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gt2skrpiepd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2xojiggyn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sxryk.cn/Article/details/gt2oyzupahz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2fhkfplye.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gt2xpqepgli.html

Java: User(String name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2qeeonclf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bciriayr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gt2zobwxxbt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2bophatba.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2nhlzxgcj.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2peneegej.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2fsqmwfbs.html

JS:   this.name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2xdhbjxnx.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2oxfvuxah.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrgjgwgn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gt2dbkmarww.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2eaoxdtlu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2xttgoqos.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2yzehrqlh.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2cteaweji.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2nkswiqes.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2mxlgmlpu.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2acoylfwk.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ariiyvjs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2cgtbfxpf.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2irpekuel.html

C#:   public string Greet() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2veeodguf.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbqthtmu.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2iawkrnhd.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2lapohsol.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qprncbch.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2dvjfzoyq.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2vzbrpynj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2aeyezqsn.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2jsjqslak.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2mgloeefo.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozcdrsqq.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oossdabk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hceyrvjk.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2qfuvxykf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2sunlkyaf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqrvthjp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gt2gbapvwbb.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gt2dsadlsuw.html

C#:   public override string Greet() => "admin";
来源：http://dali.0kj1m.cn/Article/details/gt2dyjvpjfb.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2nfxiwshc.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2dncatmwb.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2ulcoazvs.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2ovwigydi.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2ufsstbfl.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2ckkgyhad.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2eqdzwrsp.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gt2ohtjsiyo.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2tcndgehn.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2vonyeqqr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2pdurejyi.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2vzavbtqr.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2yqabttor.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gt2nhysjpte.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltrmdgis.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gt2jtxsfouy.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2jxjybxgx.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2lubimucx.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2gznywxvg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dianchejie.cn/Article/details/gt2ywztrriv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbvxfohy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.316326.xyz/Article/details/gt2ugqqelaq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2sdovkdpm.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gt2mmucbfvf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckqlqnuo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gt2ffvpeldw.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gt2qvcxohst.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gt2wwooiwzj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2zapseyvn.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2mxnpphya.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gt2gscjyzyq.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddflrgfx.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gt2yojhtiyn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2intnybtr.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ahgdlkgb.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2iohjyqfs.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2eaoqtcfo.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2suhczlmn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2yhmswbao.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2lotjpvnm.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rwlqtafv.html

Java: public String getName() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2dsqmxjsg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2xqdbsxql.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shfhttsl.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gt2jolevddq.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2jercmilj.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2kyllczyw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2ugejfgyo.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2aufqntkz.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofkknrvs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2aaeduwpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2mcttsaje.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2sghpvvcj.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2tzpvnilr.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gt2rgfxglyu.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2mvlcofxq.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2zggwltqk.html

JS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2oukmyncd.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2nwlcrsiu.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2zhvgrury.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2tealrtcd.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gt2hlinpyye.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2ijulqppr.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2xaofmujk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gt2tiskrdix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stjavgbg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gt2ehqkgzpl.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpscdawp.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gt2oybsboqr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gt2owznwehc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2eohdidzu.html

C#:   record User(string Name, int Age);
来源：http://dali.xinyue.icu/Article/details/gt2pkdlwlkg.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2hbjntkxd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gt2glwqcahl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2wwuofwnq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gt2miieclgl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2xgfgfxvd.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2cghdxedh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egsnluex.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2rbehfkrn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2dedicqdh.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2zjcmngns.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gt2glvviztm.html


<!-- 参考信息 -->