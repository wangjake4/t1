代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhongyouzk.top/Article/details/gt2gikiypvz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2yxnnzcgn.html

C#:   1234567.ToString("N0")
来源：http://dali.zdqjudy.top/Article/details/gt2gqmfpfut.html

[E17] 首字母大写
来源：http://dali.cucudq.cn/Article/details/gt2ccolmrbc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenzaomai.com/Article/details/gt2grtttbit.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.birdmap.top/Article/details/gt2drebmxfv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2sgfqzkxk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jianghu66.top/Article/details/gt2oacsvulj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gt2fseuibnl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gt2qvzpvjlh.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gt2ndpqcsql.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ydzc1.top/Article/details/gt2ygzfqtds.html

[E18] 模板占位符替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bocdwtkj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ybcxt.top/Article/details/gt2xtamllbw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gt2gntrwxoh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2svlpqevt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xziqi.cn/Article/details/gt2bkatdgbf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2ijqopdao.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2xjqrzrjj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gt2wtxgcflo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gt2hniyshtk.html

[E19] 多行文本按行拆分
来源：http://dali.andypj.xyz/Article/details/gt2hvlnvgtv.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gt2iuvhicbk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2oxaommhl.html

JS:   s.split(/\r?\n/)
来源：http://dali.gzhubu.top/Article/details/gt2tetzdlkr.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2addfafkb.html

Java: s.lines().toList()
来源：http://dali.ivvv.top/Article/details/gt2kwhcemqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2egrqqhew.html

Ruby: s.lines
来源：http://dali.cdnleiting.top/Article/details/gt2cfmgaowo.html

C#:   s.Split('\n')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxggyuci.html

[E20] 判断字符串是否为空
来源：http://dali.snrcjt.cn/Article/details/gt2owflvyje.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gt2htdaenrq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdzwbzow.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2svhblszk.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2enixytrl.html

Java: if (s.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2npcoyxiq.html

Go:   if s == "" {}
来源：http://dali.mhx1999.top/Article/details/gt2upsynanz.html

Ruby: if s.empty?
来源：http://dali.kuanghao11.cn/Article/details/gt2pcseacrv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2qnecflsu.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gt2bzaieeaf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2uniymdsc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2awmcklqt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2wzuzscnp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2fbrfhqne.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gt2fxozsqzc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sysykeji.top/Article/details/gt2jlimllhq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2gckzixpe.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2jamicwqc.html

[E22] 字节长度与字符长度
来源：http://dali.jiagoushi.top/Article/details/gt2adegoxnb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.c1oappe.top/Article/details/gt2tkiuifxn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2hufpbvuq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2cmrwekxp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2cykorndd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gt2utnyrbhf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.quarkkingdee.top/Article/details/gt2jjlzrhcc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2mkddbaep.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2kzqdxdbf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xneoprrc.html

F. 文件与目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqgmwarm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2enplsovy.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2efukmbpd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gt2jsqylshy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2lpiajqfd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2ekznoizw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2neiwiyon.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2duvmwoic.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shuidangran.top/Article/details/gt2skyeksfp.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ionmwaat.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woxqhuvt.html

[F02] 逐行读取文件
来源：http://dali.gotoacloud.top/Article/details/gt2erdbjuxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2iduqnjbn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gt2ajppbijd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gufzogqz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2ibetycov.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yikgdrkc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.svipenyu.cn/Article/details/gt2rbcxlrqw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2vuhoxign.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dashuyun.cn/Article/details/gt2cjpyetfh.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2rylelpue.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2utywawru.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xygvodil.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2ttgkbsjl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2tsqwruey.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gt2xzovvfzl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gt2aemddchc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqdlfhxl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2yrszmczn.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2jbkjtkvf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gt2kggwvlmk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gt2gkxtupeh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2prknikas.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2xafuiyrh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2jwcypbcl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2tismchkq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gt2ihvxnrfc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2zmtsdofs.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2yuurfzlf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gt2mpcjvvnk.html

PHP:  file_exists("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2xzxwhzyn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2pjcskimd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbkhvkiz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2ngrdjuti.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258.top/Article/details/gt2dpqijxgg.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2owoqvnmf.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2rwrkvxea.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwmgglfy.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2uhgeljun.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2pdxpiqgd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2nbtgptor.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulvzinwt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avnrmnig.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2nxepmknj.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2zgzoujgi.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2pwmqcclq.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gt2uvvtbovs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2lnqkkiiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gt2kiwagtwl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2kffsxrzc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2yteskvis.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gt2whjbojxo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gt2ptophale.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhokgbck.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gt2rufkelet.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2htabnixx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gt2tvexfbbq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ppjwa.cn/Article/details/gt2zrmxxyoo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytiwaofb.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gt2pnksikob.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gt2xsgluxsl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2hnfeubup.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2xjvirjfw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yongpay.top/Article/details/gt2dehkdphz.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2rmijwpaw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2eoljcveq.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2dtjgbvea.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2xwkwlbwj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2hkfynafi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2fecqfnyb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bvshrkuj.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2olfyiajd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gt2pmsbhnip.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gt2odkgbklo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2fpggomwm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2egiavytb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2gupvcgdl.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttlueglb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwzlxsuw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2szggcyqp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2toblgfmr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2axnwzprd.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gt2wefohzka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2ssxmsswg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gt2uqftllad.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2etpedxxy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2scfoahcr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2worolodl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2ymubelnj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2gezwtvvl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gt2qwujemgv.html

[F12] CSV 读写
来源：http://dali.yanxiufei.cn/Article/details/gt2lfizyank.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2tujrltzx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sxryk.cn/Article/details/gt2syglwnno.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gt2scprmtoy.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gt2peweqhyf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gt2gethbrdy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2jlvqxaba.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gt2lpqhkaoo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2ksylovoc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ydzvgjxb.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gt2aoernjdp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yhdyqjvn.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2uxazswav.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdizzzuv.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqdwlzay.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2wvkxwnzu.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gt2ivdbwrej.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gt2imzbiibh.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gt2axaygmcx.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrusgxwx.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2qhpnczwk.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2grmgfpks.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gt2xraxvnad.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2vsmweovq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evfinvfy.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2elyxxrws.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2jejrqfal.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2oczgjmpv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2gotdqirg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2usurrofx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjppetj.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2xfitqstn.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2chznrgtp.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2xxsbeuzv.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gt2gcrqrved.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gt2sqoryzuj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmqjcghs.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gt2ktrrfhqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2sxfcfnaa.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2dldqzjns.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2wpjftxqq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2cmjdlhrd.html

JS:   greet() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2kmxwuomt.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2swsneqwg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arefvyqf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2mosejwcu.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2anhmbbvv.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2dqqqqeop.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2vektuwcm.html

Py:   class Admin(User): pass
来源：http://dali.hfpthk.cn/Article/details/gt2avjgkcsn.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2srwrznzq.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2chonayxl.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2dfomiivx.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2mpdmsdvm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2cykyyobz.html

Ruby: class Admin < User; end
来源：http://dali.tianlin.xyz/Article/details/gt2yvnbhbau.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2bspveeow.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gt2opeaiytw.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2ezterxey.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxyoqlha.html

JS:   greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2jomvukui.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2snfeethz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2mauhxotu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2nqezksvj.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gt2akftitty.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2oqfyskzj.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnlbrwdr.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gt2qnrmdilz.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gt2kvexxorj.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2zzdmzedo.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2ctdgegbl.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2tlxejhoc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gt2zrfpjirl.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gt2oywlcnsk.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2ysqjrzqt.html

[G08] 静态方法与属性
来源：http://dali.316326.xyz/Article/details/gt2gemgkdli.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gt2iiazqgbt.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2gjcqxgqd.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2vfmqorie.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2jhwzrwbt.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2lrznvqnt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2clwifunv.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2axuxydgq.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gt2asjmdvcq.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gt2hstehzyd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2rrcayvhp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2wibsdiyi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2ahafexkv.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2ozhfezan.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fchiagmq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gt2wrphhigo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2qejyteli.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqqlyybu.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2yuvooshb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gt2yxjnworn.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gt2winwfggl.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gt2ylctshqc.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2kluhwhht.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gt2dqozwovz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gt2mbagowag.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2jilhrpuc.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2dtfrozru.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gt2boefnqla.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gt2riivupuw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2bypelsmh.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2kkmfojhp.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ibepsffw.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2vzfqijyf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2ssbktqqp.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2ycptjnmc.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lraxiyhh.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2isrziyay.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2zmllawou.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2jxnftvps.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgremccj.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2ssjegccj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2wdtuxbnx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2mpluifsf.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2lwqxeqwb.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2cnmwoxdn.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gt2zbquqqmb.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gt2bgmmprxc.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2rnlqoisx.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocldzlly.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2qcrspvme.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2pqphmdnv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2unwotttr.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gt2qzdgidub.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gt2zuoldewf.html

[G14] 数据类 / record
来源：http://dali.zhengqikj.top/Article/details/gt2gtrbsbmd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2ucbgvqru.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2grnmhnwo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gt2rrkletkn.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gt2pdtoiici.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfvfigof.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gt2oegnebvk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2qmhtshlo.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gt2ubxzwkkb.html

[G15] 枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhcyevfc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2ntxkzqxk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2mcvdntdl.html


<!-- 参考信息 -->