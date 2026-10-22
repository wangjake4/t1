代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.haohaochexian.top/Article/details/gt2iqftslnx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2wkrudlhs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gt2nvbrcask.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmuchlaq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigufen.top/Article/details/gt2cudyfuhp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gt2ndlmmhce.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gt2hjdjsggd.html

[E17] 首字母大写
来源：http://dali.haohaochexian.top/Article/details/gt2xihquzsz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxcgkpks.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yuxming.cn/Article/details/gt2belvievb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gt2euyqayhu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gt2xmvltdiv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2rxtfgavk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2aunqqnqq.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gt2pgzhjpbv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gt2oohxcjbm.html

[E18] 模板占位符替换
来源：http://dali.jlsjyb.cn/Article/details/gt2htdytsue.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258.top/Article/details/gt2mpbztjnm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hfpthk.cn/Article/details/gt2fsytmgbi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2vrnsmrut.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abzdyllv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aizwys.cn/Article/details/gt2ewynfjzp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jyoumei.cn/Article/details/gt2kbkvjgkm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gt2jicqarbm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gt2suhbgklh.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gt2qnsoytfn.html

Py:   s.splitlines()
来源：http://dali.zhengqikj.top/Article/details/gt2mdtispdu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2upkqzxpp.html

JS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2zybeoskh.html

TS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2fjdohpem.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gt2doefoaps.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gt2wrbqyvmb.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gt2jtdoasfc.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gt2pckaqmxq.html

[E20] 判断字符串是否为空
来源：http://dali.ydzc1.top/Article/details/gt2gvwzliya.html

Py:   if not s:
来源：http://dali.hnxiangtu.top/Article/details/gt2mhgqkvju.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yonumen.top/Article/details/gt2szdhltjm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxaikzku.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gt2qnkdsqua.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2mifmuulb.html

Go:   if s == "" {}
来源：http://dali.snrcjt.cn/Article/details/gt2sgsjnmsd.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gt2nbxaljou.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mufperin.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gt2grqtyknd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfpmyltj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2opeqdwjj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gt2fokglgwi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2jaucmvhd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2cohimspy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gt2jnkmpsjt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2fjnsdvrz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2bjqsaloy.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gt2ajwsvaph.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsihvqey.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2szkfynlr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gt2txyivixb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2lfuyjsvi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2hgorchje.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.haohaochexian.top/Article/details/gt2irmmkhxq.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2oiicyeim.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2djkwhuvt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bkdeiwvl.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gt2kwfaxtpf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2kjchujka.html

[F01] 读取整个文件
来源：http://dali.pycfn.com/Article/details/gt2rjxxktxd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jyoumei.cn/Article/details/gt2ztqusktk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2oxaxtkpp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbpjvyve.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2aaqdiwse.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2cjsovzgl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgfzy.top/Article/details/gt2kcdicobn.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2kawalogl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2amxhaswt.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gt2ympbkbhz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gt2epumjvty.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nynpedxb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gt2pdqjdsrf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2xuyigmuy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gt2vyhemnyv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtvfsyaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2plazhgza.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gt2bzgtesmw.html

[F03] 写入文件（覆盖）
来源：http://dali.tianlin.xyz/Article/details/gt2hwghrmid.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gt2avfxbcig.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2mqdcjmxq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2epmnmtrd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2awbhvqhe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gt2qybidbpc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgedvqxo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2ntuxxvtq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2kttxznfg.html

[F04] 追加写入文件
来源：http://dali.quarkkingdee.top/Article/details/gt2kppawxpr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gt2wqejykmt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cduubitf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2zqvmvpwi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2cjdwxneo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gt2wjcjrhcq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rioyfthv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aumcdmon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2jkdzzadg.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sghrcnyw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gt2axgdopgy.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wnkkqvgq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2itgerlby.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2yrhrndbv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2hxebrmyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2qobpdizz.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tzkaezgt.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2lksnpxju.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2elrzluql.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdvvrijh.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2tdfspxdf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2dgptbsiu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2konruldg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvyyjhdc.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2kjomlpnq.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbusuzwm.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2ggilyrgc.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltqiwxvv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2aliekmuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhrrdqpw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2koygpulh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2kxcqvrmn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gt2eewxofeo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gt2tuanxmnl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2otymzyvu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gt2nqxtviqm.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gt2vhvgfnut.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmelhhul.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gt2ajmwztuu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2btwwrvly.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2fxbzclvr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2qzmzwskk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gt2qtgwmddo.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2qtkufcbk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2lvajrhvo.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2uikzfoui.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2hlcrvmch.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2gdoopstf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2poragper.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2ocunkogv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2yxbcxsxc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2kmrpjsvo.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2elmdumty.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gt2wkoxnake.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gt2hvsmbpbi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2qdlwliyu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2joggsqke.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2exwbxiot.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2aouaqwui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yexjcsuh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2buysdizr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2zcanpdly.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2xgwcbpsl.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2medyunwd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2folknogi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258.top/Article/details/gt2ogylyoqz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2timqldux.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gpiomkiy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2npsmukvz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gt2fezvivuy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2cndvijdw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gt2supfzmsq.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2fundjbpp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gt2ojeguavk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sahzatki.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2yunooysw.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2zgqccabb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gt2edxpjkzy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gt2wthcfpjp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gt2edqouuby.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gt2urxogkau.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fkkhuwcv.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2qhrajllm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2luldeupb.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gt2nfkyiazh.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gt2xwsmcvin.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tflijlav.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2asjecaev.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2zbtxxixl.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2mqtkbwns.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2ayccllui.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gt2ewgnamao.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2ufwywufq.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gt2dpkelffy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2ajpoorhc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2irqqfehv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2dfmftyei.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2nzjouoao.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2lkfjlvnt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2egenghci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zycfv.cn/Article/details/gt2jsazdvyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2udxyrckn.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2atmzwlwx.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gt2njorlaiw.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2wqjuvsjx.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2cthulpbp.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gt2elosijgb.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2tslstzbz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gt2hhuzlabk.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2lbatcvcp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gt2klotrkfk.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2psnttwab.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2hszdkblz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2rrychpst.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2vklmuljv.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2kswvfhzp.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2xycjtnbn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2vkqxxcuz.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gt2lcvqdwbn.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2ixuvybgf.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gt2hocvbyhs.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2rykxcsnp.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2eopzqntx.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2pawudezu.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2grkbnbcz.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2gjhbmmvb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqegnmiw.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gt2mwxduxht.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2uhegtvuq.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xslphstc.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbrbdemk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2jhwwrrww.html

JS:   greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2gsjlxiey.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2gahtapfu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2yzzdtiqg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlhdcbjn.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2ttijxqlz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhengqikj.top/Article/details/gt2igkbxfuu.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gt2clvmymrq.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gt2rfaylphv.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2iknkwuda.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2mmaunlfz.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2qidpdfel.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2pmlrkyed.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2ddzgkxla.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2twtfrigz.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2shopcgaf.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqwimwld.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gt2xtvunbwm.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2hawbdlrt.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2bypxdlji.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zmpmtjku.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2limxitog.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2fzhbqcxq.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2fckdeqes.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2pxuygczv.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2qxzzuyjo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gt2mthtyfdw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2iwuvagix.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gt2vfgqlnet.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2exmnorar.html

Java: interface Shape { double area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dxrrtkkb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gt2yynwoskf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2qnstwovr.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gt2qhemhrfg.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gt2nmweagik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gt2ssdsocyx.html

PHP:  public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2xocgftma.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gt2iywijyhd.html

TS:   public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdaqxmng.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gt2hifedrgq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gt2rbzsjckv.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2vozvghsb.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gt2gjqvmhvf.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gt2yakgdogh.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2veslqqdg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hodfdmrk.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2hcguyrvi.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gt2jjxwbffq.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ugawqnej.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2fknmnbbo.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gt2lacnbnyx.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gt2fdimghhj.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gt2twdalqti.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2pdnfladd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2medxelnx.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2kbpakxpm.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jlvfqkzt.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2dugimvtf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2ffbyqrmy.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2vqfavsmh.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2tsyrtges.html

[G13] 判断对象类型
来源：http://dali.sufxvd.cn/Article/details/gt2mtcmcjpf.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2lnogxxdx.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2rprqfvay.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghvcoxky.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2pboevsto.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2djrwtvxm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gt2tozochaq.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gt2fpvkdzco.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2rjzrmjrn.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2bwqszjkj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gt2yrqgjvpn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2bgbzrtgc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilvczzff.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2wvxzyoze.html

Java: record User(String name, int age) {}
来源：http://dali.meibo888.top/Article/details/gt2vafflqxo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2xrepdotx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gt2sfeacpxb.html


<!-- 参考信息 -->