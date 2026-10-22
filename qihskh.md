代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.gzhubu.top/Article/details/gt2kpdoywap.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gt2ympthlcm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2rwlvbdlr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2vwlgisik.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.redwolf501.top/Article/details/gt2ymhrjrva.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gt2jfiwiocw.html

C#:   1234567.ToString("N0")
来源：http://dali.yj20258.top/Article/details/gt2ahbpupkl.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gt2ubbmpuab.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xawqyzhk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2thjwugkb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2smbyrxhm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2ynrgdwcv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hysaishi.cn/Article/details/gt2rlkndnrr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258.top/Article/details/gt2zwxvjbev.html

Ruby: s.capitalize
来源：http://dali.yongpay.top/Article/details/gt2prgggznn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.iojbl.cn/Article/details/gt2xgmyzrsh.html

[E18] 模板占位符替换
来源：http://dali.hysaishi.cn/Article/details/gt2qicfiezt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nwbrower.top/Article/details/gt2eltpwabt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gt2oprfmsbb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2kowwyazi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2xclecyhe.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sweek.top/Article/details/gt2noteclzb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2gcejfsuo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gt2iijmjmrm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vykpoaxv.html

[E19] 多行文本按行拆分
来源：http://dali.svipenyu.cn/Article/details/gt2aqtjrqtq.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gt2wrcrygws.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2fohjnvnj.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jkzblswy.html

TS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gt2rwsmnxah.html

Java: s.lines().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2cnsphptk.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258.top/Article/details/gt2tzsnuyri.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gt2welecctf.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gt2mssdhxvk.html

[E20] 判断字符串是否为空
来源：http://dali.yueranfly.top/Article/details/gt2sqdwzyxq.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gt2uepjihor.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2hkpopugk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gt2ittznykm.html

TS:   if (s === "") {}
来源：http://dali.dashuyun.cn/Article/details/gt2puyirrim.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gt2tucfukqh.html

Go:   if s == "" {}
来源：http://dali.jiagoushi.top/Article/details/gt2rfonyrpa.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2fokoyghd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cucudq.cn/Article/details/gt2agukinqh.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gt2pjbmtytz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2icmbwnwi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2uxuogvwi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2oncmiqhh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2xyesjngx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gt2cobnhzsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2wbwwgbvk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2htcoqnli.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naubedcv.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gt2gtszsskd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2wtxcogjg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2tbdfarba.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2wwigakja.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2ndqdrhqz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2odpsvxja.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zdqjudy.top/Article/details/gt2hmkcdbkb.html

Ruby: s.bytesize;  s.length
来源：http://dali.ivvv.top/Article/details/gt2ikcaqsqn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nicdgkcb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dnthvqll.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gt2jvrjhfpg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mcyxlwnd.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2buxpujxl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iosjzdce.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2yeuqbxeg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gt2ztfsmioq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2amoinvpo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2vnykchlm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gt2gmywpxfa.html

Ruby: File.read("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qcpxlfzm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgrnstal.html

[F02] 逐行读取文件
来源：http://dali.andypj.xyz/Article/details/gt2bbyqxnux.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2knacsveq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2ugwxabzz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ppmjfcbo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2dmyxtcqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgzdnhbs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdkwueuw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xuanzx.com/Article/details/gt2jptclwtu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywhtuefx.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gt2obqbnasb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gt2elwkvrhe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2gvirsyhr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2zecrleal.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2huvhszcz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2qxhcqebd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gt2iyfiqdcs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrgccgup.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2vcljibao.html

[F04] 追加写入文件
来源：http://dali.chenlongwang.top/Article/details/gt2zoqnlrsy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2kulhcivs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2aunifjyu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2gtvjwjxw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqnfvupu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2bpiiewge.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2dmsjlvvk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifgemmzq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhvgntkw.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxoyiclt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2tdxuocwf.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uprawwpo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2yshndmdv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2goofmdqq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2iesywvmm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2qdaawitf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2uaqxymlo.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grdfihhz.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frsvtnye.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2wovsytke.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2jycybszb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjujheli.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2wjeuggzk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gt2fdmerthb.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2iczmbjyp.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ifamqidr.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2cncbigrj.html

[F07] 创建目录（含多级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2rypzpxuh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2hcnpdyoq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gt2fkfpmvxx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2dsskvlcc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2xgtdocbu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2wtjyjpsw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cucudq.cn/Article/details/gt2skwqrbyq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stujcvgi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gt2uvymdjtj.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2etitegcr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gt2yormckhw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gt2mccngkkq.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2rwoiubll.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gt2aeyjisnm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2xbozakqf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2ovcrizhx.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2jzaxboaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2xhdrpodj.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gt2tglzehbv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zzixtijt.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2deazhdvx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2hmkrcymg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2abaadewo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2wsoctwje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2mrdpamue.html

Ruby: File.size("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imyvobxh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gt2cgzmrsxi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gt2mwpzjhyz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2opgwnrzq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2gxgbvqcs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2evyayoba.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2oyhusuhd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2wvfibctp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2bbkgeium.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gjsdvoms.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2akctucpp.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gt2xreddany.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2buuxfrpu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pklkguqw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2eyfbwdca.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2qjrnotil.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gt2zvzsayyp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gt2fhbcegzr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2jiykgrft.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqjtrdin.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2rhkpciki.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gt2qhyzrpvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gt2ktsukrbl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2spnpbalo.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gt2zygfalif.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2uqfhtrtg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gt2hhbxupyc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bryxwvzs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gt2enehswnz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2psobvtvl.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gt2rwpenavi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qowrntlj.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gt2zuwscsfz.html

Py:   class User: pass
来源：http://dali.mhx1999.top/Article/details/gt2tfcbibvd.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2uxhizpab.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2hmpcygfo.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2jsdzxynt.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gt2sfcudehh.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gt2bptwqexl.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gt2quexmsvc.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2uezcwlmd.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2wheianoz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2kmbdoack.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mujfpwnz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2zgrjmuxp.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gt2lxncrfza.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zjxkrnuw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymqmhgrk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2zktptmwu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdazffpf.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2ymqkzddq.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2qakawngv.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gt2lcfqzbus.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2viphascb.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gt2ijeleics.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gt2tudgsoan.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfprlvmy.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2katsstnh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqhxspjh.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2pjjoruwr.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2jwqhedgg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2swtpxiom.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2zsfqnbrm.html

TS:   greet(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmydjumo.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2zdgbuqon.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2stnzajvv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrlnwea.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gt2sgoxrtdc.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2odegxoub.html

Py:   class Admin(User): pass
来源：http://dali.316326.xyz/Article/details/gt2wwkmquec.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2bfzppbqg.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htddsgau.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ypgwjows.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2folaqvca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlzopvrq.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gt2kbbqkghn.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gt2vsasygcx.html

[G06] 重写方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbzrxprk.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2ogafkpnf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pectjpxu.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gt2pieelktj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2cgwykjek.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2prjccrey.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2iqngpawb.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2puyjncai.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2gvjqrkvd.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2qgjivfbw.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2iylnhbbp.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gt2ozehqffa.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2skffapve.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2amcbxmns.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2byrcfjcf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gt2womlppxv.html

Ruby: super
来源：http://dali.haohaochexian.top/Article/details/gt2frrlhxqn.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gt2jttxrgpu.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2vczjnfjx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gt2huraqdsm.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2sbxwaunf.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2klueyxho.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ezwvzsxv.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2yrlqyzkx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2fxzgqcgc.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2hzjelnpk.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gt2zqtahmau.html

[G09] 接口 / 抽象类
来源：http://dali.gotoacloud.top/Article/details/gt2edirkckj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gt2cwqbnfks.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kclahmvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2bbbeerct.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2thvxupps.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwodlbgx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqsylvmi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gt2gipjhqjl.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lmmfacyi.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2jbckxpix.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gt2tufmyrbx.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2ydbwrzue.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gt2sduvvjei.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2rouggmbo.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2uyazkcwk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2qbszbszo.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iultvqyt.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2joxkmpwe.html

[G11] getter / setter
来源：http://dali.yonumen.top/Article/details/gt2sliutzpe.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gt2knzossfz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2uvaxogur.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2klnjbmhw.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2zrgnckdd.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2zlloxkfk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2uhbfejqc.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gt2wbzazjvd.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pxnyttdp.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2fsgvbqgf.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gt2enjapaue.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gt2osisxyxd.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2sgjtrfrc.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnzqogrh.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ysfazohc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2espystnc.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2xcecdhah.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2tcskttni.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gt2ubrursdm.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gt2zjultdfu.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2cqcovgpi.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2dhwrgbys.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2cgdmsefd.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2hrrwdiwr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2brhgrpxx.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2hwyfuffj.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gt2xorvkkmt.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gt2iagnvsnu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2ergkfcjp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2cpcdxjhr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xziqi.cn/Article/details/gt2jroijhyy.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2jxhhsjvw.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiqzejif.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2dqsajfog.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2vtxuhdmf.html


<!-- 参考信息 -->