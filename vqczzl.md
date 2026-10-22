代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ybcxt.top/Article/details/gt2mebemexz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gt2huvugvaa.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gt2rogquaqa.html

[E17] 首字母大写
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgalcvpn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2nfheiqtf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gt2dmryvgai.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2sacdcusc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gt2gvmgbemp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gt2bnqhmzyo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sysykeji.top/Article/details/gt2geafgpqp.html

Ruby: s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2kdtvhwvv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zdqjudy.top/Article/details/gt2avjkrhyp.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2yincngfa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sxryk.cn/Article/details/gt2qoqkqrrs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ydzc1.top/Article/details/gt2btgaawfw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gt2inohqtiw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gt2ubukglst.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gt2cdlkzclr.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2mldjysbq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ivvv.top/Article/details/gt2mqnpfqcw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ajxhekgt.html

[E19] 多行文本按行拆分
来源：http://dali.316326.xyz/Article/details/gt2pwmpmozq.html

Py:   s.splitlines()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdemnzes.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nanxinkj.top/Article/details/gt2fazosrdx.html

JS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ekgvemyi.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2aosffmtc.html

Java: s.lines().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2gyyzurwi.html

Go:   strings.Split(s, "\n")
来源：http://dali.yangfankeji.com/Article/details/gt2uheaitvc.html

Ruby: s.lines
来源：http://dali.yj20258.top/Article/details/gt2gqumuxpw.html

C#:   s.Split('\n')
来源：http://dali.sufxvd.cn/Article/details/gt2swhqasuc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2eudbnjwq.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2navpwtwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2tnqwpxqz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yonumen.top/Article/details/gt2lnrgvbtd.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gt2qhowhcnf.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2tcyllkdi.html

Go:   if s == "" {}
来源：http://dali.jinqigfzy.top/Article/details/gt2nxfkvhbf.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2vmikgahw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jyoumei.cn/Article/details/gt2dtcbaofl.html

[E21] 超长截断加省略号
来源：http://dali.cheryme.top/Article/details/gt2wiaimiod.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gt2cslkfrbq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2moyhjmcx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggduhrde.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2poarardn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2hlpnyknx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2evefwmod.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2rlctmeim.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2tffpfgkw.html

[E22] 字节长度与字符长度
来源：http://dali.chenlongwang.top/Article/details/gt2ypihwhpb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gt2kznyvayz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2xdgwrzhd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2ocotqxlm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2lhzdpaeo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2nmxxqprw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgpumbut.html

Ruby: s.bytesize;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2todxqldx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2oyshjfin.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2vbrizbgq.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2coaeuriq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2itsnxvdb.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gt2vdojtjmd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.andypj.xyz/Article/details/gt2zhmgdosb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2sxenompo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gt2hothvwcf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daxiang520.top/Article/details/gt2nuwhshwz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2wwfrrvbc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pycfn.com/Article/details/gt2kierhkim.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2pkmaftmm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2zfldvvvk.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gt2plpannqo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2ukflzmui.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2molbbnee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2puljarhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aofqqulj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2xfvmlcvf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2onnbftmu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cqqwz.cn/Article/details/gt2ihjcejkd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aibaodan.cn/Article/details/gt2jhaxqikm.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gt2bvenbskq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gt2aporyabp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2ujzwknqi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gt2futemqxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozgagjsr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2jwzjhzcw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gt2tciyatlt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2pthrycvc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2acvkbsmh.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2tgmnyezy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2ualodcpj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gt2qtleahnh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2cscspvqn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2fdzwerao.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhoulong.xyz/Article/details/gt2tyhhubmu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2rjnzkkki.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gt2yjaglcel.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xziqi.cn/Article/details/gt2jmzidxwi.html

[F05] 判断文件或目录是否存在
来源：http://dali.jianghu66.top/Article/details/gt2ffthkpzt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2admkkadi.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbehilsn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2cbtbqrxp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xuvxvlvk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2ijctlgfw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2objwhluh.html

Ruby: File.exist?("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2vhqnummy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2yomdnkom.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2zkztsrds.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2uzgvozwt.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2dctkeodt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2fhfjhtxj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2audvkmiq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2zhnwamlg.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2ltakqbge.html

Ruby: File.delete("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2dmvpgeaa.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2yvibclwj.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2hjvgevxt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2ctebwrwf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2cvarwwyz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2ojvrteis.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2jfgxgajj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhirlhmf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gt2srwbcveq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2mxqjwfha.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fknjrhgn.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gt2vzssgjsy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2ecakiqvq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gt2quzbliae.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2ljyvijpt.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2epubasqi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2dtroqdrl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2bmyxkplq.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2amsgglut.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gt2jkcyhdyy.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2nblwkpcm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ptyetpqf.html

PHP:  filesize("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2evoixvbs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2neqzkddi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gt2jhpgbzmh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2dpqqpngj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2lqmitxwj.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akgzsdpw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhongyouzk.top/Article/details/gt2deqryspa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gt2lbjigskg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qdhqbqoj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2wwtlvovo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2voniglcw.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gusmgfvq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxpxrglh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2whciidgk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2lsdevxko.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2kkstejqy.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gt2sgsktqhh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2wqoutpzi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gt2rlkknzdx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2eeiddcpl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2iimmmpsz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2xoodhilp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gt2amrmoplt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohouigvw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gt2pgvgqmkk.html

[F12] CSV 读写
来源：http://dali.haohaochexian.top/Article/details/gt2mocvgjxm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2ayxlhmll.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2rafqeuyj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2jjpzmcde.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2ikaiucar.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2svuiiqxk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2ybvjrjql.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubjnipta.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2qywkqcvm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yxzyjxsu.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gt2vsfpppbh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2yyfxwhft.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gt2illhnxbe.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abudsgpb.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2zsvrbedk.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mlcmrxjn.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2jdrfozrz.html

Java: class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2eedeykoz.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gt2imjcijan.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ttjomhxv.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2heotieyj.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixoxxggt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2kvimztqq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2nsjzhddk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2vmarpsep.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdgrfvjm.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2vjcaapuz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2peyapvxg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gt2bzinjtcn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2cubvobjd.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2dfgmmjfs.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qsyfermz.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2cgizphbh.html

JS:   this.name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2akqlmwsa.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ajelosav.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjqinvup.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2ycycffbn.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kltzlrru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2zslzytgp.html

[G04] 定义方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2lpxwwpgm.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2ersfmupr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2ehnbmgtj.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlmmtbpl.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2vwgmuryg.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2yqsaotic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2kwoogltn.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gt2cqbeizus.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2oephxeio.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gt2awwqlhst.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2npldpdrh.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2exnpvsvx.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2iaynbktg.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2ejjolpzv.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2lejqgbva.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2gqueomhj.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gt2yjvjfwjb.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gt2nhmmhfmm.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2dvbwdlnq.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2sgakbdgz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2fqytkbxu.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2emxmfwbu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2bdcdhtul.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2yngjxxhy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gt2xjfhklny.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2xeauaegc.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkhtrcnu.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gt2tshqiipz.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gt2ckouqomp.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2qzgsdlza.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2drskvttb.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ivyasrjs.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2nyqyazkj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gt2gjnxznlh.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gt2pzygstfk.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2tmaadtei.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gt2corapgzl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2swiecmwu.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ezymggoz.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2adeqdgdi.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2anvgwxhl.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2golcayns.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gt2cqfetaac.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2dfcrotjw.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2brmnonac.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gt2qcetpnbx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gt2nczlvbhy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gt2yibpvmft.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gt2oqkjssus.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gt2qbyrtfzp.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2veydcxmj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2qfdzecdh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gt2xeiqkaup.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2anpuqfsq.html

[G10] 访问控制
来源：http://dali.nanxuanxn.top/Article/details/gt2arjnzndi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2rekbzzyg.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2oshrxrfx.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2hihhmrlk.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2jjgaibvp.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2xxdnpibl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2tbeswxqx.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzpcxkfo.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpdujvpx.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gt2sjmzcrfw.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gt2gwqaeipx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vstfyjjq.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpjvkzxq.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prpgruyq.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2qyouxxpi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2vsaorrbu.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gt2fuicowep.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gt2txztvmys.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2elkkxwfc.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2jbkcxfpk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2dlwlvuce.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bkpxpqfo.html

TS:   toString(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2heldthvd.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2cvwmkqmc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2mbwhnaxr.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2ibcqchvx.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gt2trjbynwj.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gt2etqnxxlm.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pwmriuyb.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qiiczssd.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2afwspags.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2ujrjyjai.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2itvxutkw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwlfqhw.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gt2zdauikue.html

C#:   u is User
来源：http://dali.cqqwz.cn/Article/details/gt2oopkrwmf.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2ichjyhxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxuanxn.top/Article/details/gt2dlshjjff.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gt2ulnzkqxc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2cecbbrua.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2vcnxizln.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2xhcannug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gt2bacdgdzx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2bzroahxw.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2osavoiav.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2vfjxgbyc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gt2fivejxtp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkmkwsvq.html


<!-- 参考信息 -->